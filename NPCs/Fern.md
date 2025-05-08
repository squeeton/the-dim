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
locations: []
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

# Fern
> [!infobox | right]+
> # Fern
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



a rootling.


a small green humanoid that came from a bramble seed and was adopted by [[The Party]].
if it becomes dangerous it is [[Darius]]'s job to put it down. 


 A child of [[Laranth]]. it is bonding to me currently, and once it does it will emulate me.
 it has a lifespan of one week.
 
it will bear fruit and i will be safe from death once it finishes its life cycle. i cannot rebond.

