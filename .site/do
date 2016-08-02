#!/bin/bash

EXPORT_DIRPATH=../compiled-pdfs/;

# Se "$1" == "compile" allora compiliamo il file .tex
if [ "$1" == "compile" ]; then
	# Allora ci muoviamo nella sua cartella ed eseguiamo latexmk
	cd $(dirname "$2");
	latexmk -pdf $(basename "$2");
	latexmk -c;
elif [ "$1" == "checkout" ]; then
	destination="$EXPORT_DIRPATH$2";
	mkdir -p $(dirname "$destination");
	cp "$2" "$destination";
else
	echo "UNRECOGNIZED OPTION";
fi
