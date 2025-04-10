---
dg-publish: false
tags:
  - SessionJournals
icon: FasBook
aliases: []
session: 
---
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

> [!infobox | right]+
> # <% tp.file.title %>
> |  Information | Links |
> | --- | --- |
> | **Session** | `VIEW[{session}][text(renderMarkdown)]` |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |
> 
## Raw Notes







## Last Session
<%*
// Set folder you want to get latest file for here
const folder = "~Sessions";
// Get all files in that folder, including nested folders
const filesInFolder = app.vault.getMarkdownFiles().filter(file => file.path.startsWith(folder));
// Sort files by ctime
filesInFolder.sort((a, b) => a.stat.ctime < b.stat.ctime ? 1 : -1);
// Get basename of latest TFile to be used in link
const latestFileName = filesInFolder[1].basename;
_%>
[[<% latestFileName %>]]




