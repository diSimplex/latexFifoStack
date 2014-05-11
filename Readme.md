# latexFifoStack

A LaTeX implementation of a combined FIFO Stack modified from Benjamin 
Bayart's excellent [LaTeX stack 
package](http://www.ctan.org/tex-archive/macros/latex2e/contrib/stack) 
from [CTAN](http://www.ctan.org).

As well as keeping Bayart's \Push and \Pop commands (which have been 
renamed to \FSPush and \FSPop and which work on the top/end of the 
FIFO/Stack), we explicitly add the ability to \FSUnshift \FSShift off 
the bottom/front of the FIFO/Stack

# Source code

The original source code [public 
releases](https://github.com/diSimplex/latexFifoStack) and the 
[development code](https://github.com/stephengaito/latexFifoStack) can 
both be found on GitHub.

# Building

This project can most easily be built using the "cook" rubygem and the 
command line command:

> cook texStyle

in the project's root directory.  This will compile the documentation, 
run the regression tests and zip the CTAN package into the directory 
ctanRepo directory.

# Copyright and LaTeX Project Public License

Copyright (C) 2014 Stephen Gaito (PerceptiSys Ltd)

This work may be distributed and/or modified under the conditions of 
the LaTeX Project Public License, either version 1.3 of this license or 
(at your option) any later version.

The latest version of this license is in 
http://www.latex-project.org/lppl.txt and version 1.3 or later is part 
of all distributions of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is Stephen Gaito.

The released source can be found at:
https://github.com/diSimplex/latexFifoStack/tree/master/texStyle

The development source can be found at:
https://github.com/stephengaito/latexFifoStack/tree/master/texStyle

This work consists of the files fifo-stack.dtx, and fifo-stack.ins. 

The command:

> pdflatex fifo-stack.ins

followed by:

> pdflatex fifo-stack.dtx

will produce the derived files: fifo-stack.sty, fifo-stack-test.tex,
and fifo-stack.pdf.

The command:

> pdflatex fifo-stack-test.tex

will regression test the fifo-stack package. Output will be found in
fifo-stack-test.lgout. If pdflatex completes with no errors, then all
regression tests passed.

# What's new

v1.0 (2014/03/24)
* Initial version extened from CTAN stack package v1.00 (on 2014/03/24)
