PDF=alda_g17.pdf

.PHONY: all clean

all: $(PDF)

$(PDF): alda_g17.tex $(wildcard **/*.tex)
	pdflatex $<
	pdflatex $<

clean:
	rm -f *.log *.dvi *.aux *.toc *.lof *.lot *.out *.bbl *.blg *.xmpi *.synctex.gz *.fls *.fdb_latexmk content/*.aux
	rm -f $(PDF)