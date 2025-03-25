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
  was an outpost that became a settlement
  buildings are out on the marsh built on top of the [[Marrow Cane]] as stilts
  eventually grew into a larger settlement

  they are known for the [[Marrow Cane]]

  they too rigid like they have a stick up their....
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
# Reedswatch
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
