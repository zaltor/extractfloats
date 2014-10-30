extractfloats
=============

A pdfLaTeX package to aid in the creation of a PDF file for each float
in a document.

To use this package:

1. First, generate the package file `extractfloat.sty` file by running 
   `pdflatex extractfloats.ins`.

2. Next, generate the documentation PDF by running 
   `pdflatex extractfloats.dtx`.

3. (optional) To install globally, `extractfloats.sty` needs to be
   copied into the `tex/latex/extractfloats` subdirectory inside your
   `texmf` directory.  If this subdirectory doesn't exist, please
   create it.  For the documentation, please copy `extractfloats.pdf`
   into the `doc/` subdirectory inside your `texmf` directory.
