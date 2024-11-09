---
tags:
  - FolderNotes
  - About
---
> [!NOTE] ABOUT
> #### DESCRIPTION
> This is for references, useful information, and knowledge that doesn’t require ongoing attention but might be useful for future projects or areas.

> [!important] FOLDER
> #### OUTLINE
> ```dataviewjs
> const pdfFiles = app.vault.getFiles().filter(file => file.extension === 'pdf');
dv.table(["File", "Path"], pdfFiles.map(file => [dv.fileLink(file.path), file.path]));
> ```