---
img: z_config/images/ImagePlaceholder.png
uses: as a steel alternative. makes tools and weapons.
description: "moss that can be treated to become hard. when it grows it hardens extremely tough. "
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
# Hardmoss
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



