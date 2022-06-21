# PyMuPDF documentation

Welcome to the PyMuPDF documentation. This documentation relies on [Sphinx](https://www.sphinx-doc.org/en/master/) to publish HTML docs from markdown files written with [restructured text](https://en.wikipedia.org/wiki/ReStructuredText) (RST).


## Updating the documentation

Within `source` update the associated `.txt` files which are in RST format. These files represent the corresponding document pages. 



## Building HTML documentation

From the "docs" location run:

`sphinx-build -b html source build/html `

This then creates the HTML documentation within "build/html". 


## Building PDF documentation


First ensure you have [rst2pdf](https://pypi.org/project/rst2pdf/) installed:
	

`pip install rst2pdf`


Then run:


`sphinx-build -b pdf source build/pdf`

This will then generate a single PDF for all of the documentation within "build/pdf".


---


For full details see: [Using Sphinx](https://www.sphinx-doc.org/en/master/usage/index.html) 



