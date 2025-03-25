---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasEarthAmericas
aliases: []
img: z_config/images/ImagePlaceholder.png
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
---


> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**NPCs** | `INPUT[inlineListSuggester(optionQuery("NPCs"), useLinks(partial)):npcs]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |Aliases|`INPUT[list:aliases]`|
> |Pronunciation|`INPUT[text:pronunciation]`|
> |**Description** |`INPUT[textArea:description]`|
# The Slurry Lake
> [!column|2 no-title]
>>### Overview
>>| Pronunciation | Also Known AS|
>>| ----- | ----- |
>>|`VIEW[{pronunciation}][text(renderMarkdown)]`|`VIEW[{aliases}][text(renderMarkdown)]`|
>>
>> ### Description
>> `VIEW[{description}][text(renderMarkdown)]`
>>  
>
>>`VIEW[{img}][image]`
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

