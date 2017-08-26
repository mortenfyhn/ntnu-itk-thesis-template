# ntnu-itk-thesis-template
A template for theses at NTNU's Department of Engineering Cybernetics (and other places). It looks like this:

![Screenshot](screenshot.png)

## How to use
Pretty straightforward---just copy everything and replace the contents with your thesis.

* `bib/`: Put your bibliography files here.
    - You should use probably use [Mendeley](https://mendeley.com) or [Zotero](http://zotero.org) or [EndNote](https://endnote.com) or something, so you don't have to write these manually.
* `img/`: Put your graphics here.
* `tex/`: Put your tex source files here. I usually create one file per chapter.
* `config.sty`: Put all your `usepackage` commands and other document configuration stuff here.
* `Thesis.tex`: The main thesis source file, which includes all your chapters, etc.

## How it's configured

* Page size B5.
* Font size 10.
* All chapters begin on a right hand page.
* Abstracts, lists of figures, etc. may start on a left or right hand page.
* The [Libertine](https://en.wikipedia.org/wiki/Linux_Libertine) font is used for text and math.
* The [Inconsolata](https://en.wikipedia.org/wiki/Inconsolata) font is used for code listings.
