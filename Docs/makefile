all:
	latex Informepi.tex
	latex Informepi.tex
	bibtex Informepi
	latex Informepi.tex
	latex Informepi.tex
	dvips -o Informepi.ps Informepi.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true Informepi.ps Informepi.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl
