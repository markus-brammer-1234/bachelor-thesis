# Bachelor Thesis 


## Tools 

This thesis is written in LaTeX with Texmaker. 


## Setup 

The setup is very simple: The file `Main.tex` contains the entire thesis while
the file `Preamble.tex` contains all the settings for the project. The latter 
includes packages, statics definitions, etc. 

It is a given that `Main.tex` will become very large. Here, TeXStudio is a 
great tool: The `Structure` pane allows for easy navigation and sections can be
folded in the editor. 

Two more TeX-files exist in the root folder: `Sources.bib` and 
`Frontmatter.tex`. The first is for bibliography; the latter contain all the content 
that appears before the table of contents. This frontmatter file is inspired 
by the `Frontmatter` folder in the [DTU Thesis Template][0]. 

Finally, the folder `Figures` is simply a place to store all the figures to be 
included in the thesis. 


[0]: https://gitlab.gbar.dtu.dk/latex/dtutemplates/tree/master/templates/Thesis