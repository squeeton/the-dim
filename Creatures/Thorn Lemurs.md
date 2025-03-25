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
description: cat sized small monkeys, they normally curl up in balls when sleeping and can be dangerous traps for unobservant travelers.  they bunch up and are defensive. easy to step on
uses: quills. they are like syringes and their insides can be used for medicine
defenses: their quills are a neurotoxin that can coalesce into medicine after death or removal
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

# Thorn Lemurs
> [!column|2 no-title]
>
>>
>> ### Overview
>>| Pronunciation | Also Known AS|
>>| ----- | ----- |
>>|`VIEW[{pronunciation}][text(renderMarkdown)]`|`VIEW[{aliases}][text(renderMarkdown)]`|
>>### Description
>>  `VIEW[{description}][text]`
>>### Uses
>>  `VIEW[{uses}][text]`
>>### Defenses
>>  `VIEW[{defenses}][text]`
>
>> 
>> `INPUT[imageSuggester(optionQuery("")):img]`

# Other Details
