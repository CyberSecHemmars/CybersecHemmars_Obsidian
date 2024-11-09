---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is for daily journaling and logs.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
TABLE
file.path as "Path"
FROM "{06} - DAILY"
SORT file.name ASC
WHERE !contains(file.tags, "#FolderNotes")