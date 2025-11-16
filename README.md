pkginfograb
==========

Collecting package's info in a regular way

For more details,  see the documentation,
[pkginfograb.pdf](http://mirrors.ctan.org/macros/latex/contrib/pkginfograb/doc/pkginfograb.pdf)
	
--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*).

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/pkginfograb).

## Usage
### Stable version
Just place
```latex
  \usepackage{pkginfograb}
```

in the preamble and compile away.

## Contacting Author

For bug reports and enhancement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/pkginfograb/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/pkginfograb

-------------
Copyright 2025-present by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consist of the files

* pkginfograb.sty
    - the package itself

* README.md  (this file)
    - quick introduction

* pkginfograb.tex
    - package documentation
* pkginfograb.pdf
    - documentation in PDF format
    
-------------

## Change log
* Version 1.2 (this)
    - a bit of expansion control
    - new commands to set package's info and call \ProvidesExplPackage or \ProvidesExplClass

* Version 1.1
    - collecting the list of packages settled and a command to map over them.
    - adding conditional commands for testing if (package's) info set.

* Version 1.0
    - Initial release at CTAN.
