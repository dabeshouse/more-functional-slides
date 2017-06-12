more-functional-slides

Uses pandoc and reveal.js

Installed pandoc with homebrew

> brew install pandoc

Full installation of reveal.js in this directory as well.


To produce the slides:

> pandoc -s --mathjax -i -t revealjs -V theme:black -c override.css slides.md -o slides.html --slide-level 2
