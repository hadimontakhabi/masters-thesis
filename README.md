# masters-thesis

To compile the document and get the pdf, run the following command:

$ pdflatex main.tex


After adding a new citation, complie like this:

$ pdflatex main.tex
$ bibtex main.aux
$ pdflatex main.tex
$ pdflatex main.tex

