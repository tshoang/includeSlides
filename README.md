# includeSlides package #

This repository contains packages for including slides from external
PDFs into LaTeX beamer presentation.

# Installation #

The package is already pre-compiled. However, in the case where it is
needed for recompiling, a gradle build script has been provided. The
users can simply issue the following command:

    ./gradlew (on *nix systems)
or

	gradlew.bat (on Windows systems)

This will perform the following:

  - To create the style files *includeSlides.sty*

  - To create the documentation *includeSlides.pdf*.

The style file *includeSlides.sty* should be copied to some proper
location for LaTeX to find it later (e.g.,
"/usr/local/share/texmf/tex/").

# Documentation #

File *includeSlides.pdf* contains the source of the style file in the
classical literate programming style.

License
-------

This file may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3c of this license
or (at your option) any later version. The latest version of this
license is in:

   http://www.latex-project.org/lppl.txt

and version 1.3c or later is part of all distributions of LaTeX
version 2008/05/04 or later.

This work has the LPPL maintenance status `author-maintained'.

The Current Maintainer of this work is T.S. Hoang.

--
Copyright (C) 2018 by Thai Son Hoang
<T dot S dot Hoang at ecs dot soton dot ac dot uk>
