# polyhedral_faq
sources for [Polyhedral Computation FAQ](https://cddlib.github.io/polyhedral_faq)

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
make4ht -u polyfaq.tex "mathml,mathjax"
bibtex polyfaq
make4ht -u polyfaq.tex "mathml,mathjax"
```
