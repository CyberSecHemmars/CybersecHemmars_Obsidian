---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is for metadata about the vault itself. Anything that relates to how the vault is structured, templates used, workflows, and how information are managed.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
TABLE
file.path as "Path"
FROM "{99} - META"
SORT file.name ASC
WHERE !contains(file.tags, "#FolderNotes")