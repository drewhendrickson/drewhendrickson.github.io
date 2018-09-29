bibliography.html : bibliography.bib
	bibtex2html -s apalike -no-keys -t "Drew Hendrickson papers" -nf pdf "pdf" bibliography.bib
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg


clean:
	rm -f *.html