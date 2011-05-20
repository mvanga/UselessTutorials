TOP := exbook.tex
SRC := basics.tex
DVI := $(patsubst %.tex, %.dvi, $(TOP))
all: $(DVI) 

$(DVI): $(TOP) $(SRC)
	latex $<
	latex $<
	dvipdfm $@
	evince $@

clean:
	rm -rf *.aux *.dvi *.log *.toc *.pdf
