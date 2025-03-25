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
description: "a fishing community settled on a  tethered group of massive lily pads and wreckage in the middle of Crescent Lake. Folks from Hardmire say people from Rat King can't smell their own stink. "
maptack: 5
groups: []
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
# Rat King
> [!infobox | right]+
> # Rat King
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