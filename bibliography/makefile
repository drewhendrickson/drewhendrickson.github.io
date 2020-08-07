bibliography.html : bibliography.bib
	bibtex2html -s apalike -no-keys -u -t "Drew Hendrickson papers" -nf pdf "pdf" -nf psyarxiv "PsyArXiv" -nf osf "OSF" bibliography.bib
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg


clean:
	rm -f *.html