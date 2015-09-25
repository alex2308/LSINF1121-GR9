pdf:
	pdflatex report.tex
	bibtex report
	pdflatex report.tex
	pdflatex report.tex -file-line-error-style
	gnome-open report.pdf

clean:
	rm *.aux *.log *.out *.bbl *.blg
