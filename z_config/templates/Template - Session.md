<%*
const sessions = app.vault.getMarkdownFiles().filter(file => file.path.startsWith("~Sessions"));
// Sort files by ctime
sessions.sort((a, b) => a.stat.ctime < b.stat.ctime ? 1 : -1);
// Get basename of latest TFile to be used in link
const latestSession = sessions[1].basename;
const sessionCount = sessions.length;
_%>

<% "---" %>
dg-publish: false
tags:
  - SessionJournals
icon: FasBook
aliases: []
session: <% sessionCount %>
lastSession: "[[<% latestSession %>]]"
<% "---" %>

> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**Tags**|`INPUT[list:tags]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**NPCs** | `INPUT[inlineListSuggester(optionQuery("NPCs"), useLinks(partial)):npcs]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Locations** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Groups** | `INPUT[inlineListSuggester(optionQuery("Groups"), useLinks(partial)):groups]`|
> |**Events** | `INPUT[inlineListSuggester(optionQuery("Events"), useLinks(partial)):events]`|
> |**Description** |`INPUT[textArea:description]`|
> | **Session** |`INPUT[number:session]`|
> | **Last Session** |`INPUT[text:lastSession]`|

> [!infobox | right]+
> # <% tp.file.title %>
> |  Information | Links |
> | --- | --- |
> | **Session** | `VIEW[{session}][text(renderMarkdown)]` |
> | **Last Session** | `VIEW[{lastSession}][text(renderMarkdown)]` |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |
> 
## Raw Notes

