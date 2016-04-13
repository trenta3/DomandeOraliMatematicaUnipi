# Makefile per la compilazione del progetto LaTeX
# Creato mer 13 apr 2016, 11.12.59, CEST

.PHONY: alldocuments Fisica2Interno 

alldocuments: 
	wget https://github.com/trenta3/stdmdoc/raw/master/stdmdoc.cls -O stdmdoc.cls
	pdflatex --shell-escape Fisica2Interno.tex
	rm -f *.aux *.log *.out

Fisica2Interno:
	wget https://github.com/trenta3/stdmdoc/raw/master/stdmdoc.cls -O stdmdoc.cls
	pdflatex --shell-escape Fisica2Interno.tex
	rm -f *.aux *.log *.out

# Fine del Makefile
