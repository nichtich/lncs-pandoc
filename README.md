lncs-pandoc
===========

a slightly modified pandoc latex version to be conform with lncs

based on <https://github.com/studentkittens/lncs-pandoc>

Copy llncs.latex to $HOME/.pandoc/templates/. 

~~~sh
$ pandoc --biblio=paper.bib --biblatex -N -o paper.tex --template=llncs paper.md 
$ latexmk -xelatex -pdf paper.tex 
~~~
