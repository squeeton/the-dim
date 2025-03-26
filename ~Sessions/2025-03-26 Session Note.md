---
dg-publish: false
tags:
  - SessionJournals
icon: FasBook
aliases: []
session: 1
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

## Raw Notes
> [!infobox | right]+
> # 2025-03-26 Session Note
> |  Information | Links |
> | --- | --- |
> | **Session** | `VIEW[{session}][text]` |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |
> 

-----------------------------------------------------------------------






## Last Session
[[2025-03-04 Session Note]]




