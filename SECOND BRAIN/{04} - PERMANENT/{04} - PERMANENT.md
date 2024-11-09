---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is where long-term valuable information that doesn’t change are stored. It is a digital archive for knowledge I am keeping indefinitely.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
TABLE
file.path as "Path"
FROM "{04} - PERMANENT"
SORT file.name ASC
WHERE !contains(file.tags, "#FolderNotes")