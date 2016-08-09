# Chalmers thesis class for LaTeX

- If you find something odd, wrong or lacking, please email me; Mikael Öhman <mikael.ohman@chalmers.se>. But *please* do NOT email me about standard latex questions, but only things specific to the chalmers-thesis document class.

- These files have been distributed through: http://www.github.com/Micket/chalmers

- No files with the `Example` prefix are necessary, but recommended to include as they serve as documentation.

- Sources for images comes from `src_figures` which aren't necessary for end users of the themes.

- If you are using the Chalmers linux system, you need to add texlive 2010 which is in unsup. In short, add `./chalmers/sw/unsup/texlive/bashrc.inc` to `~/.bashrc` or `~/.profile`. The file contains paths to the newer version of latex.

- Template should work with either `lualatex` (possible `xelatex`) or `pdflatex`. With a recent version of `lualatex` installed, it should be preferred as it will give smaller files with nicer fonts (and more features).
