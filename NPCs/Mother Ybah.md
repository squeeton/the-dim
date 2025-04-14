---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags:
  - NPC
icon: FasUserAstronaut
iconColor: 
aliases:
  - Ybah
Personality: []
Nimbus: ""
Path: none
Order: none
img: z_config/images/missing.jpg
arcana: []
gnosis: 1
items:
  - "[[Everpot]]"
locations:
  - "[[Hardmire]]"
pronunciation: " Mother - Yah-Bah"
motivation: |-
  She is in charge of the children
  she wants to provide the culture and ethos for the children
weakness: ""
nimbusSignature: ""
nimbusImmediate: ""
nimbusLongTerm: ""
traits:
  - "#Caring"
description: |-
  elderly woman keeping the Everpot going.
  takes care of the kids and tells stories about The Dim.
  shes in charge of the children's education.
  The main danger is the wildlife.

  in charge of the hearth.
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

# Mother Ybah
> [!infobox | right]+
> # Mother Ybah
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






skinny but hard womanin her 80s
long white hair, tied back with scarf
one eye missing, no fucks given about it

has lots of busy tasks
her main time is telling stories keeping the kids out of trouble or their parents business
