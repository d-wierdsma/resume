# resume
My base resume, built using LaTeX and compiled using PDFLatex

## How to run
docker run --rm -v "$PWD":/data blang/latex:ubuntu pdflatex Daniel-Wierdsma-Resume.tex

## TODO
Eventually set up Circle CI on this so that I can just commit the tex file and it will build the pdf version all of its own.
