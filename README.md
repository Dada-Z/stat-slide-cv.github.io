# stat-slide-cv.github.io

**Hello!**

This repo is for STAT850 Homework 10: Professional Communication.

Here is my slides: 
- [Beamer/LaTeX](https://github.com/Dada-Z/stat-slide-cv.github.io/blob/main/part1_beamer.pdf)
- [HTML-based (reveal.js)](https://github.com/Dada-Z/stat-slide-cv.github.io/blob/main/part1_html.html)

Here is my [CV](https://github.com/Dada-Z/stat-slide-cv.github.io/blob/main/cvDZ.pdf). 

- The bib does not work when compile pdf using cvDZ.tex file. To solve this issue, execute the following commands in Terminal: 

- pdflatex cvDZ.tex 
- biber cvDZ 
- pdflatex cvDZ.tex

Self Check:

- I compile pdf in cvDZ.tex first, but error occured in bib
- Following above step to compile cvDZ.tex
- Open .qmd file, Render, check cv link in PDF file
- Open .Rmd file, Knit, check cv link.

P.s. I first worked on all files in the "10-professional-Dada-Z" repo (private), then moved the necessary files here and generated the final output.
