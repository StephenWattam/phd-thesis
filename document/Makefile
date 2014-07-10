CC=
FLAGS=

LATEX= pdflatex -interaction=nonstopmode -halt-on-error
BIBTEX= bibtex
DVIPS= dvips
PS2PDF= ps2pdf

SRC := $(shell egrep -l '^[^%]*\\begin\{document\}' *.tex | sed -e 's/.tex//')
PSF = $(SRC).ps

all : pdf 

pdf :
	$(LATEX) $(SRC) && $(BIBTEX) $(SRC) && $(LATEX) $(SRC) && $(LATEX) $(SRC)


clean :
	rm *.bbl *.aux *.blg *.dvi *.log *pdf *.ps
