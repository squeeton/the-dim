---
ImportedOn: Saturday, 18 December 2021 8:41:47 PM
dg-publish: false
tags: 
icon: FasExclamation
img: z_config/images/missing.jpg
start-date: 2025-03-25
end-date: 2025-03-26
aliases: []
repercussions: ""
causes: ""
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
> |**Causes** |`INPUT[textArea:causes]`|
> |**Repercussions** |`INPUT[textArea:repercussions]`|
> |**Start date**|`INPUT[datePicker:start-date]`|
> |**End date**|`INPUT[datePicker:end-date]`|
# Sporefall
> [!infobox | right]+
> # Sporefall
> `VIEW[{img}][image]`
> ## Notables
> |  Information | Links |
> | --- | --- |
> | **Aliases** | `VIEW[{aliases}][text(renderMarkdown)]` |
> | **NPCs** | `VIEW[{npcs}][link]` |
> | **Items** | `VIEW[{items}][link]` |
> | **Locations** | `VIEW[{locations}][link]` |
> | **Groups** | `VIEW[{groups}][link]` |
> | **Events** | `VIEW[{events}][link]` |


## Description
>>  `VIEW[{description}][text(renderMarkdown)]`

## Causes

>>  `VIEW[{causes}][text(renderMarkdown)]`


## Repercussions
>>  `VIEW[{repercussions}][text(renderMarkdown)]`

#### Scratchpad





the fins of the [[Gray Beards]] get jostled and makes a heavy sticky fluid rain of spores.
its this sticky substance that envelops a seed. it can stick to you and eventually drown you 