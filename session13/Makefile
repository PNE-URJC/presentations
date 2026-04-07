LATEXTOPDF=pdflatex
PROGRAM=Session13
MV=mv

all: $(PROGRAM).pdf

$(PROGRAM).pdf:
	$(LATEXTOPDF) 000-session13.tex
	$(LATEXTOPDF) 000-session13.tex
	$(MV) 000-session13.pdf $(PROGRAM).pdf
clean:
	rm -frv *.aux *.nav *.out *.toc *.log *.snm *.vrb *~
clobber:
	rm -frv *.aux *.nav *.out *.toc *.pdf *.log *.snm *.vrb *~
test:
	$(LATEXTOPDF) -draftmode 000-session13.tex

.PHONY: all $(PROGRAM).pdf clean clobber test
