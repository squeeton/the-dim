---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags:
  - NPC
icon: FasUserAstronaut
iconColor:
aliases: []
Personality: []
Nimbus: ""
Path: none
Order: none
img: z_config/images/missing.jpg
arcana: []
gnosis: 1
items: []
locations:
  - "[[Reedswatch]]"
  - "[[Reed's Rest]]"
pronunciation: " "
motivation: ""
weakness: ""
nimbusSignature: ""
nimbusImmediate: ""
nimbusLongTerm: ""
traits: []
description: ""
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
> |**Motivations** |`INPUT[textArea:motivation]`|
> |**Weaknesses** |`INPUT[textArea:weakness]`|

# Nyello Frost
> [!infobox | right]+
> # Nyello Frost
> |  Information | Links |
> | --- | --- |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |

> [!column|2 no-title]
>
>>
>>### Description
>>  `VIEW[{description}][text(renderMarkdown)]`
>>  ### Traits
>> `VIEW[{traits}][text(renderMarkdown)]`
>
>> 
>> `INPUT[imageSuggester(optionQuery("")):img]`


#### Scratchpad




The current innkeeper for [[Reed's Rest]]

lean man, scar covering two thirds of his face .
big beard. hair shaved back.
hardness to his frame. got that farmer strength.
