# The `blocktable` package

This LaTeX package provides an extension to David Carlisle and David Kastrup's `longtable` package. It defines a derived environment `blocktable` that will *visually* chunk (not to confuse with `longtable`'s chunk mechanism) the table's content into equally large blocks of rows.

After calling

    \usepackage{blocktable}

in the preamble in the manuscript you can use the environment like

    \begin{blocktable}[<blocksize>]{<col spec>}
      \caption{<table title>}\\
      <opt head spec>\\
      <opt foot spec>\\
      ...
    \end{blocksize}

This is version 0.1 of the package.

Copyright (C) 2015 by Ruben Giannotti 
<ruben dot giannotti at gmx dot net>

---

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either
version 1.3c of this license or (at your option) any
later version. The latest version of this license is in
  http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions
of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is Ruben Giannotti.

This work consists of the files
  chaprange.dtx 
  chaprange.ins
and the derived file chaprange.sty.


To install the package

 1. run `latex blocktable.ins`
 2. move 'blocktable.sty' to locations where LaTeX will find it
