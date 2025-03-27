---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasEarthAmericas
aliases:
  - home
img: z_config/images/missing.jpg
npcs: 
items:
  - "[[Hardmoss]]"
overview: ""
cssclasses:
  - wide-table
pronunciation: ""
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
maptack: 1
groups:
  - "[[The Party]]"
  - "[[The Lyre]]"
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
# Hardmire
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
population of 26 people