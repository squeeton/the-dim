---
img: z_config/images/ImagePlaceholder.png
uses: ""
description: ""
pronunciation: ""
mysteries: []
weight: ""
price: ""
aliases: []
---

> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**NPCs** | `INPUT[inlineListSuggester(optionQuery("NPCs"), useLinks(partial)):npcs]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Locations** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Groups** | `INPUT[inlineListSuggester(optionQuery("Groups"), useLinks(partial)):groups]`|
> |Events | `INPUT[inlineListSuggester(optionQuery("Events"), useLinks(partial)):events]`|
> |Aliases|`INPUT[list:aliases]`|
> |**Description** |`INPUT[textArea:description]`|
> |**Uses** |`INPUT[textArea:uses]`|
> |**Weight** |`INPUT[text:weight]`|
> |**Price** |`INPUT[text:price]`|
> |**Type** |`INPUT[Type][inlineListSuggester:type]`|
# <% tp.file.title %>
> [!infobox | right]+
> # <% tp.file.title %>
> `VIEW[{img}][image]`
> ## Notables
> |  Information | Links |
> | --- | --- |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |


> [!column|2 no-title]
>> ### Description
>> `VIEW[{description}][text(renderMarkdown)]`
>>
>> ### Uses
>> `VIEW[{uses}][text(renderMarkdown)]`
>
>> |  Detail | Info |
>> | --- | --- |
>> | **Weight** | `VIEW[{weight}][link]` |
>> | **Price** | `VIEW[{price}][link]` |
>> | **Type** | `VIEW[{type}][link]` |


#### Scratchpad



