---
img: z_config/images/ImagePlaceholder.png
uses: ""
description: " tall fungi that only grow in water and have spindly root-like structures that reach down into the muck to anchor them. Has a symbiotic relationship with [[Great Mire Beasts]]."
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
# Swamp Tower
> [!column|2 no-title]
>> ### Description
>> `VIEW[{description}][text(renderMarkdown)]`
>>
>> ### Uses
>> `VIEW[{uses}][text(renderMarkdown)]`
>
>>`VIEW[{img}][image]`


## Overview
**Price**: Placeholder

**Weight**: Placeholder



