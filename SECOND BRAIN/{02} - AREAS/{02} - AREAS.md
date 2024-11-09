---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> These are areas of responsibility I plan to maintain over time. They don’t have a defined deadline like projects but need consistent attention.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
TABLE
file.path as "Path"
FROM "{02} - AREAS"
SORT file.name ASC
WHERE !contains(file.tags, "#FolderNotes")