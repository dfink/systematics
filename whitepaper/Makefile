all :
	latex whitepaper.tex
	bibtex whitepaper
	latex whitepaper.tex
	latex whitepaper.tex
	dvips -o whitepaper.ps -t letter whitepaper
	ps2pdf whitepaper.ps
	rm -f *.aux *.blg *.log *.dvi *~ *Notes.bib


latex -interaction=nonstopmode :
	latex -interaction=nonstopmode fermiics

clean :
	rm -f *.aux *.blg *.log *.dvi *.bbl *.ps *.pdf *~ *.bbl


xxx :
	-tar cvf xxx.tar --files-from xxx_files
	-gzip xxx.tar

