---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasUserAstronaut
iconColor: 
aliases:
  - Dayshia
Personality: []
Nimbus: ""
Path: none
Order: none
img: z_config/images/anya.PNG
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
> |**Can be Found In** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Pronunciation**|`INPUT[text:pronunciation]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**Traits**| `INPUT[Personality][inlineListSuggester:traits]`|
> |**Description** |`INPUT[textArea:description]`|
> |**Motivations** |`INPUT[textArea:motivation]`|
> |**Weaknesses** |`INPUT[textArea:weakness]`|

# Anya
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
> [!column|4 no-title]
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
>
>>### Npcs
>> `VIEW[{npcs}][link]` 

# Other Details
