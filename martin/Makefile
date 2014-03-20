PT=pdflatex
IDX=makeindex
BIBX=bibtex
MK=latexmk

all: uebl1.pdf
all: uebl2.pdf

uebl1.pdf:
	${MK} -pdf uebl1.tex

uebl2.pdf:
	${MK} -pdf uebl2.tex

clean:
	rm -rf *.aux *.log *.toc *.pdf *.idx *.out *.ilg *.ind *.slg *.ist *.syi *.gnuplot *.glo *.syg *.table
