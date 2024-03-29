# ACM CHI 2021 template for R Markdown
**_UPDATE, 16 Aug 2022: Quarto, the successor to R Markdown, comes with an [ACM template](https://quarto.org/docs/journals/formats.html). Go and use this instead! :)_**

This R package provides a template for writing ACM CHI Proceedings papers in R Markdown, and compiling to PDF via the LaTeX templates from the ACM Master LaTeX Template (v. 1.71).

## Requirements
- a LaTeX installation
- R and RStudio

## How to use
For general advice on how to use R Markdown for academic writing, see e.g. https://ulyngs.github.io/oxforddown/

- download a copy of this repository (click the green 'Code' button, then 'download zip')
- open **chi_2021_template.Rproj** in RStudio
![open chi_2021_template.Rproj](screenshots/1_folder.png)
- replace **sample-bibliography.bib** with your own bibliography
- replace the content in **main.Rmd** with your own fantastick work
- click the 'Knit' button in RStudio to compile to pdf
![open main.Rmd](screenshots/2_main.png)
![compile to pdf with the 'knit' button](screenshots/3_compiled.png)

**NOTE: include the initial *setup_output* code chunk at the top of your .Rmd file, as it creates custom chunk options that allow you to e.g. add image descriptions for visually impaired readers.**
