---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is where completed projects, inactive areas, or finished tasks go. It is the vault’s storage for things that no longer need active attention but are still needed for referencing.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
TABLE
file.path as "Path"
FROM "{07} - ARCHIVES"
SORT file.name ASC
WHERE !contains(file.tags, "#FolderNotes")