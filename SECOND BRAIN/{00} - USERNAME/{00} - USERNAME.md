---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is my primary hub, it includes my vision, mission and guidelines for using the vault effectively, It also serves as a dashboard for everything in my vault, with links to all other folders.

> [!important] VAULT
> #### OUTLINE
> ```dataview
> TABLE
> file.path as "Path"
> FROM "{00} - HEMMARS"
> SORT file.name ASC
> WHERE !contains(file.tags, "#FolderNotes")
> ```
