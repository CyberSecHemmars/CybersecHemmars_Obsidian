---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is for short-term goals and tasks that have specific outcomes.

> [!important] FOLDER
> #### OUTLINE
> ```dataview
> TABLE
> file.path as "Path"
> FROM "{01} - PROJECTS"
> SORT file.name ASC
> WHERE !contains(file.tags, "#FolderNotes")
> ```