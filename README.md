# Oregon State University Beamer Theme

## Description

Author: Jeremy Lilly

_A custom Beamer theme for Oregon State University._

## Usage

To use, place all five `.sty` files and the `images` directory into your working directory and add

`\usetheme{OSU}`

to the preamble of your main Beamer presentation `.tex` file.

### User Defined Macros

This theme allows the user to define the following macros that are used throughout the document:

- `title`
- `subtitle`
- `author`
- `department`
- `institute`
- `titlegrapic`

For example:

```latex
\title[Short Title]{Long Title}
\subtitle{Subtitle}
\author{Jane Doe\inst{1} \and John Doe\inst{2}}
\department{Mathematics}
\institute{
    \inst{1}Very Fancy University \\
    \inst{2}Another Fancy University
}
\titlegraphic{\includegraphics[scale=0.05]{images/placeholder.png}}
```

Note that not all these must be defined. The user may define whichever they like, and the document will change appearance accordingly.  

## Compilation

This theme uses OSU's official fonts, and as such should be complied with **LuaLaTeX** or **XeLaTeX**. Further, `Georgia` and `Verdana` must be installed fonts for the document to compile.

However, if you do wish to compile with **pdfLaTeX**, you may do so, and the theme will use the LaTeX's default serif and sans-serif fonts in place of `Georgia` and `Verdana`.

## Helpful Resources

- [An Introduction to Beamer](https://www.overleaf.com/learn/latex/Beamer_Presentations:_A_Tutorial_for_Beginners_(Part_1)%E2%80%94Getting_Started)
- [Beamer Documentation](http://tug.ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf)
- [Beamer Structure Guide](http://www.cpt.univ-mrs.fr/~masson/latex/Beamer-appearance-cheat-sheet.pdf)

