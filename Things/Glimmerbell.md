---
img: z_config/images/ImagePlaceholder.png
uses: |-
  its just pretty
  decorative.
description: |-
  yellow flower that hangs upside down
  flows out slightly has fixed things on the inside

  faintly glowing on the inside
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
# Glimmerbell
> [!column|2 no-title]
>> ### Description
>> `VIEW[{description}][text(renderMarkdown)]`
>>
>> ### Uses
>> `VIEW[{uses}][text(renderMarkdown)]`
>
>>`VIEW[{img}][image]`


## Overview

yellow flower that hangs upside down
flows out slightly has fixed things on the inside

faintly glowing on the inside
uses:
its just pretty
decorative. 