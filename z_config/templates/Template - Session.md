---
dg-publish: false
tags:
  - timeline
  - SessionJournals
icon: FasBook
---
> [!data-layer]- Metadata
>
> |                                       |                                  |
>| ----- | ----- |
>| **Img**: |`INPUT[imageSuggester(optionQuery("")):img]`|
> |**NPCs** | `INPUT[inlineListSuggester(optionQuery("NPCs"), useLinks(partial)):npcs]`|
> |**Groups** | `INPUT[inlineListSuggester(optionQuery("Groups"), useLinks(partial)):groups]`|
> |**Items** | `INPUT[inlineListSuggester(optionQuery("Things"), useLinks(partial)):items]`|
> |**Associated Locations** | `INPUT[inlineListSuggester(optionQuery("Locations"), useLinks(partial)):locations]`|
> |**Description** |`INPUT[textArea:description]`|

## Session Overview 
 
Brief session overview.

# What's Here
> [!column|4 no-title]
>
>>
>> ### NPCs
>> `VIEW[{npcs}][link]`
>>  
>
>> ### Groups
>> `VIEW[{groups}][link]`  
>
>> ### Associated Locations
>> `VIEW[{locations}][link]`  
>
>> ### Items
>> `VIEW[{items}][link]`
 

## What Worked 
 
- Small description.
- 
- 
- 

## Last Session
<%*
// Set folder you want to get latest file for here
const folder = "~Sessions";
// Get all files in that folder, including nested folders
const filesInFolder = app.vault.getMarkdownFiles().filter(file => file.path.startsWith(folder));
// Sort files by ctime
filesInFolder.sort((a, b) => a.stat.ctime < b.stat.ctime ? 1 : -1);
// Get basename of latest TFile to be used in link
const latestFileName = filesInFolder[1].basename;
_%>
[[<% latestFileName %>]]




