---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is for capturing quick notes or ideas that may or may not evolve into something more substantial.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
TABLE
file.path as "Path"
FROM "{05} - FLEETING"
SORT file.name ASC
WHERE !contains(file.tags, "#FolderNotes")