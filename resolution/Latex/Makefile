pdf:
	pdflatex tp1-academicos.tex

ignorando-errores:
	pdflatex -interaction=nonstopmode tp1-academicos.tex
bibliografia:
	pdflatex tp1-academicos.tex
	bibtex tp1-academicos.tex
	pdflatex tp1-academicos.tex
	pdflatex tp1-academicos.tex

clean:
	- rm -f *.log *.soc *.toc *.aux *.out  main.idx *.bbl *.bbg *.dvi *.blg *.lof *.nav *.snm *~

