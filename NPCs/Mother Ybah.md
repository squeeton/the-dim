---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasUserAstronaut
iconColor: 
aliases: []
Personality: []
Nimbus: ""
Path: none
Order: none
img: z_config/images/ImagePlaceholder.png
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
> |**Can be Found In** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Pronunciation**|`INPUT[text:pronunciation]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**Traits**| `INPUT[Personality][inlineListSuggester:traits]`|
> |**Description** |`INPUT[textArea:description]`|
> |**Motivations** |`INPUT[textArea:motivation]`|
> |**Weaknesses** |`INPUT[textArea:weakness]`|

# Mother Ybah
> [!column|2 no-title]
>
>>
>> ### Overview
>>| Pronunciation | Also Known AS|
>>| ----- | ----- |
>>|`VIEW[{pronunciation}][text(renderMarkdown)]`|`VIEW[{aliases}][text(renderMarkdown)]`|
>>### Description
>>  `VIEW[{description}][text]`
>
>> 
>> `INPUT[imageSuggester(optionQuery("")):img]`

# Personality
> [!column|3 no-title]
>
>>
>> ### Traits
>> `VIEW[{traits}][text(renderMarkdown)]`
>
>> ### Motivations
>> `VIEW[{motivation}][text]`
>
>>### Weaknesses
>> `VIEW[{weakness}][text]`

# Other Details
