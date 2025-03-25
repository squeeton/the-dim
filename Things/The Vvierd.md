---
img: z_config/images/ImagePlaceholder.png
uses: ""
description: ""
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
# The Vvierd
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



