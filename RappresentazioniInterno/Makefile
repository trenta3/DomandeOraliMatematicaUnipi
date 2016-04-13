# Makefile per la compilazione del progetto LaTeX
# Creato mer 13 apr 2016, 11.13.10, CEST

.PHONY: alldocuments RappresentazioniInterno 

alldocuments: 
	wget https://github.com/trenta3/stdmdoc/raw/master/stdmdoc.cls -O stdmdoc.cls
	pdflatex --shell-escape RappresentazioniInterno.tex
	rm -f *.aux *.log *.out

RappresentazioniInterno:
	wget https://github.com/trenta3/stdmdoc/raw/master/stdmdoc.cls -O stdmdoc.cls
	pdflatex --shell-escape RappresentazioniInterno.tex
	rm -f *.aux *.log *.out

# Fine del Makefile
