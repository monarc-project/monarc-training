BASE_NAME=index
OUTPUT=_build


pdf:
	pdflatex -interaction=nonstopmode *.tex

clean:
	rm *.toc *.log *.snm *.aux *.nav *.out *.vrb || true

clean-all: clean
	rm *.pdf
