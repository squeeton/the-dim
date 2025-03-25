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
description: Alligator-like beasts that create lairs in the tendrils of Towers. Their wiggling and burrowing between the tendrils releases spores that attach to the Mire Beasts and eventually drive them mad. When their rage ends, a new Tower grows from their corpse.
uses: When their rage ends, a new Tower grows from their corpse.
defenses: "Alligator-like beasts "
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

# Great Mire Beasts
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
