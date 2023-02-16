# Quarto extension for IRD

This extension is inspired by :
- [Hikmah(حكمة) quarto templates](https://github.com/andrewheiss/hikmah-academic-quarto)
- [Quarto extension for INRAE](https://github.com/davidcarayon/quarto-inrae-extension)

## Installing the extension for a new document or project

You will need to do this to get all the folders with images, tex and scss files and a prefilled quarto template.

```bash
quarto use template ob7-ird/quarto-ird-extension
```

## Installation for an existing document

You may also use this format with an existing Quarto project or document to download the `_extensions` folder.

```bash
quarto install extension ob7-ird/quarto-ird-extension
```



### Usage

A template in .Qmd format will be automatically created with the name entered in the terminal. The choice of the desired output format is made in YAML by adding the format as a suffix to `ird-*`. 

The possible formats for the slides are : `{revealjs,pptx,beamer}`

The possible formats for documents are : `{docx,pdf,html}`

A minimal example is :

```
title: "Titre de la présentation"
subtitle: "Sous-titre de la présentation"
author: "Auteur de la présentation"
date: "Lieu | Date"
format: ird-pptx
```

More complete examples are described in the following files:
- [ird-testing-document.Qmd](ird-testing-document.qmd)
- [ird-testing-presentation.Qmd](ird-testing-presentation.qmd)

## TODO

- [ ] Support the revealJS format
- [ ] Support the beamer format
- [ ] Support the PDF format
- [ ] Support the book/report format
- [X] Support the HTML format