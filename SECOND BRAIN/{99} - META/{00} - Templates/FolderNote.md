---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> ...

> [!important] VAULT
> #### OUTLINE
> ```dataview
> TABLE
> file.path as "Path"
> FROM "FolderName"
> SORT file.name ASC
> WHERE !contains(file.tags, "#FolderNotes")
> ```

Note: Change the folder name in the dateview.