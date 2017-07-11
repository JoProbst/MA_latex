Code Thesis Notes
=============

Date: 2017-11-07


Style guides
------------
  - [Wikipedia, Book Design](http://en.wikipedia.org/wiki/Book_design)
  - [The Chicago Manual of Style](http://www.chicagomanualofstyle.org)
  - [Writing a Thesis with LaTex](http://www.tug.org/pracjourn/2008-1/mori/) or material.
  - [Writing for Computer Science](https://eng.kuleuven.be/english/education/reporting/writing-for-computer-science-zobel.pdf) or material.
  

Plotting
--------
  - [Gnuplot](http://gnuplot.info/)
  - [Matplotlib](http://matplotlib.sourceforge.net/)
  - [R](http://www.r-project.org/)


Compilation
-----------
  1. Commands:
  ```
    pdflatex thesis
    bibtex thesis
    pdflatex thesis
    pdflatex thesis
    pdflatex thesis
  ```
  2. This should create the file thesis.pdf.
  3. If not, make sure you have all the require packages installed (see webisthesis.cls).
  4. If everything works like it should, you should not be forced to change anything in webisthesis.cls at all.
