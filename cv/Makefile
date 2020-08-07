
LATEX=pdflatex
BIBTEX=bibtex
BIBER=biber
TGT=jpscv.pdf

MAIN=jpscv.tex

ALLTEX=$(wildcard *.tex)
ALLBIB=$(wildcard *.bib)

all: $(TGT)

$(TGT): $(ALLTEX) $(ALLBIB)
	latexmk -pdf jpscv.tex

clean:
	rm *.pdf *.fls *.aux *.fdb_latexmk *.log *.fls *.fdb_latexmk *.run.xml *.out *.bbl *.bcf *.blg



