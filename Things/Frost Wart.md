---
img: z_config/images/ImagePlaceholder.png
uses: ""
description: |-
  moderate sized plant
  looks like a blue cactus
  instead of spikes it has holes like a sponge
pronunciation: ""
mysteries: []
---

> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**Mysteries** |`INPUT[inlineListSuggester(optionQuery("Mysteries"), useLinks(partial)):mysteries]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**Description** |`INPUT[textArea:description]`|
> |**Uses** |`INPUT[textArea:uses]`|
> |**Price** |`INPUT[textArea:price]`|
> |**Weight** |`INPUT[textArea:weight]`|
# Frost Wart
> [!column|2 no-title]
>> ### Description
>> `VIEW[{description}][text(renderMarkdown)]`
>>
>> ### Uses
>> `VIEW[{uses}][text(renderMarkdown)]`
>
>>`VIEW[{img}][image]`


## Overview
