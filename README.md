LatexModules
============

Modules for Latex preambles.

These modules can be loaded into your preamble.
Each modules should contain all required packages to run.

Installation
------------
Download it here: [**Latest build**](https://github.com/Limro/LatexModules/releases/latest) and place it in a folder called ```LatexModules```

Place them in a folder close to your working directory:

```
+ .\
	+ LatexModules
		- CiteSetup.tex
		- FigureSetup.tex
		- ...
	+ Documentation
		- Main.tex
		- Preamble
		+ Figures
			- Dummy.png
		- References.bib
```

### Important installation note

**If the LatexModules folder's location is changed folder-wise from the current setup (not as seen above), you must go to the ``Preamble.tex`` file and change the line ``\newcommand{\modulesPath}{../../../LatexModules/}`` to point at your location.

If you place them as above, let it be ``\newcommand{\modulesPath}{../LatexModules/}``**

Head to the [memoir example](Examples/Memoir) or the [article example](Examples/Article) to learn how to use them.

* Papers are not listed supported yet. 

* Article is recommended for normal pages under 15 pages.

* Memoir is recommended for 15 pages and above.