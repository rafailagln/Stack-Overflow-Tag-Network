.SUFFIXES:.eps .pdf .gz .data .dot

report.pdf: document.tex 
	pdflatex -shell-escape document
	mv document.pdf report.pdf

clean:
	rm -f document.aux report.pdf document.blg document.toc document.run.xml  *.log *.out *pyg
