Code Thesis Notes
=================

Date: April 4th, 2020


Science Craftsmanship
---------------------
  - [How to write a great research paper](https://www.microsoft.com/en-us/research/academic-program/write-great-research-paper/)
  - [Things a scientist is suppposed to know](https://github.com/philippbayer/Things-a-scientist-is-suppposed-to-know) or material.
  - [Resources to Help Global Equality for PhDs in NLP / AI](https://github.com/zhijing-jin/nlp-phd-global-equality)

Technical Writing Guides
------------------------
  - [Google's Technical Wrting Courses for Engineers](https://developers.google.com/tech-writing)
  - [Writing a Thesis with LaTex](http://www.tug.org/pracjourn/2008-1/mori/) or material.
  - [Writing for Computer Science](https://archive.org/details/springer_10.1007-978-0-85729-422-7/mode/2up) or material.

Organizing Literature
------------------------
See our [guide](https://git.webis.de/code-generic/code-webis-faq#how-to-do-literature-research) on literature research.

Style Guides
------------
  - [The Chicago Manual of Style](http://www.chicagomanualofstyle.org)
  - [Wikipedia, Book Design](http://en.wikipedia.org/wiki/Book_design)


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
