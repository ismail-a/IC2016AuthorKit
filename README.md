# AuthorKit - Internet Conference 2016
CRC (Camera Ready Copy) for the proceeding of Internet Conference 2016 (IC2016) should be meet a criteria same as an preprint of Elsevier Journal. Please follow this instruction.

Download [Elsarticle Bundle](http://www.ctan.org/tex-archive/macros/latex/contrib/elsarticle) from CTAN.
Important files to edit CRC for IC2016 are as follows.
* elsarticle.dtx, elsarticle.ins
  * Source files of a style file elsarticle.sty
* elsarticle-num.bst
  * Bibtex style file for Elsevier Journal
  * Bibliography for IC2016 paper should be enumerating style
* doc/elsdoc.pdf
  * A document of elsarticle.sty

Compile elsarticle.sty
```
latex elsarticle.ins
```

elsarticle.sty requires psyr.tfm. If your TeX environment doesn't have, download and install [mdwfonts](https://www.ctan.org/tex-archive/macros/latex/contrib/mdwfonts?lang=en) from CTAN.

Right here you ready to use ic2016.tex.
You don't need to modify documentclass options for both preprint and CRC.
```
\documentclass[final,3p,times,twocolumn]{elsarticle}
```
