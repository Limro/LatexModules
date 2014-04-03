LatexModules
============

Modules for Latex preambles

These modules can be loaded into your preamble.
Each modules should contain all required packages to run

Example
-------
Your tree looks like this:

+ Document
	+ Modules
		- ...
		- FigureSetup.tex
		- ...
	- Main.tex
	- Preamble.tex

Your Main.tex would look like this:

```latex
\documentclass[a4, english]{article}
\input{Preamble}

\begin{document}
\dots
\end{document}
```

Then your preamble would be:

```latex
\input{LatexModules/FigureSetup} %Note: "LatexModules" is your name of the directory
...
\title{Latex Modules setup}
```

That is all you need.