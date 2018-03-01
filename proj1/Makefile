filename=proj1

pdf:	ps
	ps2pdf ${filename}.ps

ps:	dvi
	dvips ${filename}.dvi

dvi:
	latex ${filename}


clean:
	rm -f ${filename}.{ps,pdf,log,aux,dvi}
