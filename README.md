UCD Thesis - Latex Templates
=====================

About
------------------------
The following set of files are the components needed to write your thesis or dissertation using Latex for the University of California, Davis

Originally based on the File for a general UC Dissertation / Thesis
Modfied specifically to the UCD thesis class by Shwaine <shwaine@shwaine.com>

2006 - More recent changes by Dylan Beaudette
2010 Clarification and posting to github by Alex Mandel <tech@wildintellect.com>
2011 E-filing tweak by Jason Moore
2014 Style updates to fit recent requirements
(See the Changelog for more details)

Contact us with questions and updates, we've posted the source on github so it's easier to accept changes and allow people to post their own variations.

Preview of the Stock Build
------------------------
[![PDF Status](https://www.sharelatex.com/github/repos/wildintellect/ucdthesis/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/wildintellect/ucdthesis/builds/latest/output.pdf)

How to write your thesis
------------------------
 * Download Source (button above)
 * Using your favorite Latex Editor
	* Edit the Chapter files, add more if you need (also add reference in the thesis.tex)
	* Edit the Abstract and Title matter documents
 * Build your latex document using pdflatex
	* Run latex thesis.tex (rerun if the table of contents isn't updating)
	* Run bibtex thesis.tex (rerun when you change refs)
		* Run pdflatex thesis.tex
		* Re-Run bibtex
	* Run pdflatex (Re-run when you want to see edit changes
 * To get a bibliography you need to run bibtex on your main document.
 	* If you have bibliographies per chapter you also need to run bibtex per chapter
	* After running bibtex on everything rerun pdflatex 

 * There are many optional sections: use the % character to toggle commenting out parts you don't need.
	* Dedication
	* Acknowledgments
	* Preface
