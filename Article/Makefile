
all: main.pdf

main.pdf: main.tex biblio.bib why3lang.sty decoupage_code.ml
	rubber -d main.tex

clean:
	rm -f main.aux main.blg main.bbl main.out main.log main.pdf
