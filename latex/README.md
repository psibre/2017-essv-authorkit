LaTeX Author Kit for ESSV 2017
==============================

At the top of your main LaTeX file, declare the class options with
```
\documentclass[12pt,a4paper]{article}
```

Copy the following files into the directory of your LaTeX paper:
- `essv.sty`
- `essv.bst`
- `babelbst.tex`
- `englbst.tex`
- `germbst.tex`

Apply the ESSV style to your article with `\usepackage{essv}`.
Please see `template.tex` for a full example.

Language, Encoding
------------------

The language can be switched to German using `\selectlanguage{ngerman}` (and back to
English with `\selectlanguage{english}`).

The package assumes **UTF-8** encoding of the LaTeX source files. If you use any special
characters (i.e., umlauts, etc.) and need to save your file in another encoding (e.g.,
Latin-1) for some reason, you will need to insert the command `\inputencoding{latin1}`
(substitute appropriate encoding name) after loading this package.

Requirements
------------

This package requires the following LaTeX packages; they should be available in any
modern LaTeX installation.
- [babel](https://www.ctan.org/pkg/babel)
- [caption](https://www.ctan.org/pkg/caption)
- [doi](https://www.ctan.org/pkg/doi)
- [fancyhdr](https://www.ctan.org/pkg/fancyhdr)
- [fontenc](https://www.ctan.org/pkg/fontenc)
- [geometry](https://www.ctan.org/pkg/geometry)
- [graphicx](https://www.ctan.org/pkg/graphicx)
- [hyperref](https://www.ctan.org/pkg/hyperref)
- [iflang](https://www.ctan.org/pkg/iflang)
- [inputenc](https://www.ctan.org/pkg/inputenc)
- [mathptmx](https://www.ctan.org/pkg/mathptmx)
- [natbib](https://www.ctan.org/pkg/natbib)
- [setspace](https://www.ctan.org/pkg/setspace)
- [titlesec](https://www.ctan.org/pkg/titlesec)
- [titling](https://www.ctan.org/pkg/titling)
