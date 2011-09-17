tabfigures - Using tabular figures with LaTeX
=============================================

The tabfigures package is a collection of patches for using
tabular figures in some LaTeX environments where numbers should
line up vertically such as the table of contents and enumerations.

Usage
-----

To use this package, include

    \usepackage[<options>]{tabfigures}

in the preamble of your LaTeX document. See the PDF documentation for
the available options and other details.

Installation
------------

To install the package and its documentation in your home texmf tree, run:

    make install

If you want to use a different texmf tree, you can specify it using the
variable TEXMFDIR:

    make install TEXMFDIR=/usr/local/texlive/texmf-local

Afterwards, you may need to regenerate the file database:

    texhash

License
-------

Copyright (c) 2007 by Andreas Bühmann  
Copyright (c) 2011 by Michael Ummels <michael.ummels@rwth-aachen.de>

This work may be distributed and modified under the terms and conditions of the
[LaTeX Project Public License][LPPL], version 1.3c or greater (your choice).

[LPPL]: http://www.latex-project.org/lppl/

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is Michael Ummels.

This work consists of the files tabfigures.dtx, tabfigures.ins and
the derived files tabfigures.sty and tabfigures.pdf.

All other files distributed with these sources are in the public domain.
