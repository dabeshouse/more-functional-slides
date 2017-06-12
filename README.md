more-functional-slides

Uses [pandoc](http://pandoc.org/) and [reveal.js](https://github.com/hakimel/reveal.js/)

Installed pandoc with homebrew

> brew install pandoc

Used full installation of reveal.js in this directory as well.


Produced the slides with:

> pandoc -s -i -t revealjs -V theme:black -c override.css slides.md -o slides.html --slide-level 2

-s standalone

-i incremental
