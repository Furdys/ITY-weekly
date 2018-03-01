filename=proj2

pdf: 
	pdflatex ${filename}
	pdflatex ${filename}

dvi:
	latex ${filename}
	bibtex ${filename}||true
clean:
	rm -f ${filename}.{ps,pdf,log,aux,out,dvi,bbl,blg}

