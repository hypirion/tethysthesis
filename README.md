# Tethys Thesis

<p align="center">
  <img src="fig/the-ocean-sky.jpg" alt="The Ocean Sky"/>
</p>

Tethys Thesis is a LaTeX template for computer science theses and project
documentation. An example of the template can be shown
[here](http://hypirion.com/pdf/tethysthesis.pdf).

## Introduction

Tethys Thesis is a template heavily based upon my own workflow on projects and
LaTeX experience taylored towards computer scientists. It may not suit you, but
at least it suits me well.

Notable choices include:

* Bibliography is handled with biblatex, not bibtex
* For listings, Minted is used instead of lstlistings
* For algorithms, the package *algpseudocode* is used
* Running `make repeatedly` runs latexmk, making it easier to do "agile" LaTeX
  development

## Setup

You have to install both the latexmk and a boatload of LaTeX packages. In
addition, if you want to use minted, you'll have to install pygments as well. I
tend to just do

```bash
sudo apt-get install texlive-full latexmk python-pygments
```

on Debian-based systems.

## License

Source Copyright © 2014 Jean Niklas L'orange. Licensed under the LaTeX Project
Public License, version 1.3 or later. See COPYING for details.

*"The Ocean Sky"* Copyright © 2013 Desmond Wong. *"The Ocean Sky"* is licensed
under a
[Creative Commons Attribution-NonCommercial 3.0 Unported License][cc-by-nc].
 
[cc-by-nc]: http://creativecommons.org/licenses/by-nc/3.0/
