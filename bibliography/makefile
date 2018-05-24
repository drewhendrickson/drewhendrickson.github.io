bibliography.html : bibliography.bib
	bibtex2html -s apalike -no-keys -t "Drew Hendrickson papers" -nf pdf "pdf" bibliography.bib
	rm *.aux
	rm *.bbl
	rm *.blg


clean:
	rm -f *.html