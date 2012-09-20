all :
	latex systematics.tex
	bibtex systematics
	latex systematics.tex
	latex systematics.tex
	latex systematics.tex
	dvips -o systematics.ps -t letter systematics
	ps2pdf systematics.ps
	rm -f *.aux *.blg *.log *.dvi *~ 


latex -interaction=nonstopmode :
	latex -interaction=nonstopmode fermiics

clean :
	rm -f *.aux *.blg *.log *.dvi *.bbl *.ps *.pdf *~ *.bbl


xxx :
	-tar cvf xxx.tar --files-from xxx_files
	-gzip xxx.tar

