OVERVIEW

  Camlp5 is a preprocessor-pretty-printer of ocaml.

  It is compatible with all versions of ocaml from 1.07 to 4.07.0 (when
  they compile), and jocaml 3.12.0 to 3.12.1.

  This Camlp5 version is 7.06.

INSTALL

  Read the file INSTALL to compile.

DOCUMENTATION

  The directory doc/htmlp contains the sources of the full documentation.
  To build it, cd doc/htmlp, and:
  - for its html version, type "make", result in directory ../html
  - for its latex version, type "make tex", result camlp5.tex
  - for its ps version, type "make ps", result camlp5.ps
  - for its pdf version, type "make pdf", result camlp5.pdf
  - for its info version, type "make info", result camlp5.info*

DEVELOPPERS

  The file DEVEL gives information for people who want to make changes
  in Camlp5, or who are just curious of how it is implemented. The same
  explanations are also in the chapter "Camlp5 sources" in the documentation.

PROBLEMS

  If you have problems to compile your source files with this version of
  Camlp5, the reason can be that there the new type 'location' is now
  abstract. Consider looking at the file UPGRADING.

AUTHOR

  Daniel de Rauglaudre <daniel.de_rauglaudre@inria.fr>
