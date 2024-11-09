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
> FROM "{02} - AREAS/CYBERSECURITY/BUG BOUNTY"
> SORT file.name ASC
> WHERE !contains(file.tags, "#FolderNotes")
> ```
