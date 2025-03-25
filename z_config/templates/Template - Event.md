---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags:
  - timeline
icon: FasExclamation
img: z_config/images/ImagePlaceholder.png
---
> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**NPCs** | `INPUT[inlineListSuggester(optionQuery("NPCs"), useLinks(partial)):npcs]`|
> |**Mysteries** |`INPUT[inlineListSuggester(optionQuery("Mysteries"), useLinks(partial)):mysteries]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Locations** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
# <% tp.file.title %>
Text description of the event

## Details
> [!column|3 no-title]
>
>>
>> ### NPCs
>> `VIEW[{npcs}][link]`  
>>  
>
>> ### Locations
>> `VIEW[{locations}][link]`  
>
>> ### Items
>> `VIEW[{items}][link]`  
