all:
	# latex document
	# latex document
	# dvips -t letter document
	# ps2pdf document.ps

	platex rt-cv
	platex rt-cv
	dvipdfmx rt-cv
	dvipdfmx -f texfonts.map -p letter rt-cv

clean:
	rm -f *.aux *.bbl *.blg *.log rt-cv.dvi rt-cv.ps rt-cv.pdf 
