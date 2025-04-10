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
items: []
locations: []
pronunciation: " "
motivation: ""
weakness: ""
nimbusSignature: ""
nimbusImmediate: ""
nimbusLongTerm: ""
traits: []
description: 3 feet long, 4 inches wide diameter brown snakes live in the mud/water
defenses: venemous. causes paralysis
uses: |-
  harvest skin for odd items
  can eat their meat
---
> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**Can be Found In** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Pronunciation**|`INPUT[text:pronunciation]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**Traits**| `INPUT[Personality][inlineListSuggester:traits]`|
> |**Description** |`INPUT[textArea:description]`|
> |**Uses** |`INPUT[textArea:uses]`|
> |**Defenses** |`INPUT[textArea:defenses]`|

# Mud Slithers
> [!column|2 no-title]
>
>>
>> ### Overview
>>| Pronunciation | Also Known AS|
>>| ----- | ----- |
>>|`VIEW[{pronunciation}][text(renderMarkdown)]`|`VIEW[{aliases}][text(renderMarkdown)]`|
>>### Description
>>  `VIEW[{description}][text(renderMarkdown)]`
>>### Uses
>>  `VIEW[{uses}][text(renderMarkdown)]`
>>### Defenses
>>  `VIEW[{defenses}][text(renderMarkdown)]`
>
>> 
>> `INPUT[imageSuggester(optionQuery("")):img]`

# Other Details
