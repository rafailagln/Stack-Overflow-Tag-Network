.SUFFIXES:.eps .pdf .gz .data .dot

report.pdf: document.tex 
	latexmk -pdf -jobname=report -pdflatex="pdflatex -interaction=nonstopmode" -use-make document.tex

clean:
	rm -f report.aux report.pdf *.blg *.toc document.run.xml  *.log *.out *pyg report.fls report.fdb_latexmk




