LATEXTOPDF=pdflatex
PROGRAM=Session16
MV=mv

all: $(PROGRAM).pdf

$(PROGRAM).pdf:
	$(LATEXTOPDF) 000-session16.tex
	$(LATEXTOPDF) 000-session16.tex
	$(MV) 000-session16.pdf $(PROGRAM).pdf
clean:
	rm -frv *.aux *.nav *.out *.toc *.log *.snm *.vrb *~
clobber:
	rm -frv *.aux *.nav *.out *.toc *.pdf *.log *.snm *.vrb *~
test:
	$(LATEXTOPDF) -draftmode 000-session16.tex

.PHONY: all $(PROGRAM).pdf clean clobber test
