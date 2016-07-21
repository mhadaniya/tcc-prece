filename=template

tcc:
	pdflatex ${filename}.tex
	bibtex ${filename}
	pdflatex ${filename}.tex
	pdflatex ${filename}.tex

clean:
	rm -f ${filename}.{ps,pdf,log,aux,out,dvi,bbl,blg,lot,lof,toc,brf,out.ps}
