all: exbook.dvi

%.dvi: %.tex
	latex $<
	latex $<
	dvipdfm $@
	evince exbook.pdf

clean:
	rm -rf *.aux *.dvi *.log *.toc *.pdf
