---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags:
  - Location
icon: FasEarthAmericas
aliases: []
img: z_config/images/missing.jpg
npcs:
  - "[[Pic]]"
  - "[[Nyello Frost]]"
items:
overview: ""
cssclasses:
  - wide-table
pronunciation: ""
description: ""
maptack: 4
groups: []
locations:
  - "[[The Dim]]"
  - "[[Reedswatch]]"
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
> |Map Tack|`INPUT[number:maptack]`|
# Reed's Rest
> [!infobox | right]+
> # Reed's Rest
> `VIEW[{img}][image]`
> ## Notables
> |  Information | Links |
> | --- | --- |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **Map Tack** | `VIEW[{maptack}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |
> 


> [!column]
>>  ## Description
>> `VIEW[{description}][text(renderMarkdown)]`
>
>> ## Additional Notes
>> 
>> 

#### Scratchpad




A Local Inn in [[Reedswatch]]
lots of windows, merry sounding place. a jolly in.

modest stage with performers.
large tank of brown murky water in glass.
murky water with plants and dirt on bottom. wooden jug next to it. 

behind the bar 