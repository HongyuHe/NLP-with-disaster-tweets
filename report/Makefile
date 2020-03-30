OUTDIR=build
FLAGS=-bibtex -outdir=$(OUTDIR)
report: report.tex
	latexmk $(FLAGS) -pdf report.tex

clean:
	latexmk $(FLAGS) -c

cleanall:
	latexmk $(FLAGS) -C
