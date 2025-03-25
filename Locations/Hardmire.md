---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasEarthAmericas
aliases:
  - home
img: z_config/images/ImagePlaceholder.png
npcs: 
items:
  - "[[Hardmoss]]"
overview: ""
cssclasses:
  - wide-table
pronunciation: hard my-er
description: |-
  population: 20ish people
  communal living.
  slogan: Take what you can give what you can
  .
  covered in giant mushrooms
  water filters down, 
  muggy, cooler at night. comfortable temperature
  .
  swamps no more than 1 meter deep.
  .
  lots of hunting to be done
  tanning hides plenty. materials are used to make tools.
   no glass.
   some windows may have membranes. lots of ambient light and biolumenescence
  village is named after [[Hardmoss]], the towns main crop and export.
  these guys are judgmental assholes 
  .
  [[The Lyre]] often visit this town.
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
# Hardmire
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





