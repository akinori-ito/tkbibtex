# Improvement of tkbibtex

Akinori Ito, 22 May 2018

[tkbibtex](https://ctan.org/tex-archive/biblio/bibtex/utils/tkbibtex/) is a tcl/tk program for editing BibTeX file, written by P. I. Corke in March, 2000.
I used to use JabRef for editing BibTeX files, but one day I had a problem that JabRef does not start
(it might be a problem of Java) and had difficulty to input and edit BibTeX file.
I searched any alternative program of JabRef and eventually found tkbibtex.

As the original site of the author was already lost, this program only remains in CTAN. I found this program useful, but at the same time I found several points to be improved. Thus I made a little hack to this program and decided to release it at github.

## Release Note

- 22 May, 2018:
    - Citelistbox (the first window) is changed so that the entries are alphabetically sorted.
    - DOI field is added.
