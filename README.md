# polyhedral_faq
sources for Polyhedral Computation FAQ

Building pdf
============

```
xelatex polyfaq
bibtex polyfaq
xelatex polyfaq
xelatex polyfaq
```

Building html
=============

```
make4ht polyfaq.tex "mathml,mathjax"
bibtex polyfaq
make4ht polyfaq.tex "mathml,mathjax"
```
