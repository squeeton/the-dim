---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasUserAstronaut
iconColor: 
aliases:
  - " "
Personality: []
Nimbus: ""
Path: none
Order: none
img: z_config/images/ImagePlaceholder.png
arcana: []
gnosis: 
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
philosophy: ""
methods: ""
mysteries: []
npcs:
  - "[[Darius Ravenscar]]"
  - "[[Ajax]]"
  - "[[Anya]]"
  - "[[Dirk Stonejaw]]"
---
> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**Members** | `INPUT[inlineListSuggester(optionQuery("Characters"), useLinks(partial)):npcs]`|
> |**Associated Locations** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Mysteries** | `INPUT[inlineListSuggester(optionQuery("Mysteries"), useLinks(partial)):mysteries]`|
> |**Pronunciation**|`INPUT[text:pronunciation]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**Traits**| `INPUT[Personality][inlineListSuggester:traits]`|
> |**Description** |`INPUT[textArea:description]`|
> |**Philosophy** |`INPUT[textArea:philosophy]`|
> |**Methods** |`INPUT[textArea:methods]`|
# The Party
> [!column|2 no-title]
>
>>| Pronunciation | Also Known AS|
>>| ----- | ----- |
>>
>> ### Description
>>  `VIEW[{description}][text(renderMarkdown)]`
>
>> 
>> `INPUT[imageSuggester(optionQuery("")):img]`

# Additional Information
> [!column|3 no-title]
>
>>
>> ### Members
>> `VIEW[{npcs}][link]`  
>>  
>
>> ### Locations
>> `VIEW[{locations}][link]`  
>
>> ### Items
>> `VIEW[{items}][link]`  
>

# Details
> [!column|2 no-title]
>
>>
>> ### Philosophy
>> `VIEW[{philosophy}][text(renderMarkdown)]`
>>  
>
>> ### Methods
>> `VIEW[{methods}][text(renderMarkdown)]`
# Free Text