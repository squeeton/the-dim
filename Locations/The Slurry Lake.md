---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasEarthAmericas
aliases: []
img: z_config/images/missing.jpg
npcs: 
items: 
overview: ""
cssclasses:
  - wide-table
pronunciation: ""
description: |-
  a village/town the whole area is suncken in 30/40 ft
  houses built right into the walls of The Slurry Lake
  the rest of the floor is a large lake of slurry 2-4 meters deep
  people harvest the slurry to be used as a fertilizer for plant growth and sell it as an export

  they are assumed to be lazy cuse the land does the work
  and people call them wetfoots
maptack: 2
locations:
  - "[[The Dim]]"
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
> |Map Tack|`INPUT[number:maptack]`|
> |**Description** |`INPUT[textArea:description]`|
# The Slurry Lake
> [!infobox | right]+
> # <% tp.file.title %>
> `VIEW[{img}][image]`
> ## Notables
> | Description |  Links |
> | ---- | --- |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **Map Tack** | `VIEW[{maptack}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |
> 

>>### Overview
>>| Map Tack | Also Known AS|
>>| ----- | ----- |
>>|`VIEW[{maptack}][text(renderMarkdown)]`|`VIEW[{aliases}][text(renderMarkdown)]`|
>>
>> ### Description
>> `VIEW[{description}][text(renderMarkdown)]`
# What's Here
> [!column|2 no-title]
>
>>
>> ### NPCs
>> `VIEW[{npcs}][link]`
>>  
>
>
>> ### Items
>> `VIEW[{items}][link]`

## Additional Details
Placeholder