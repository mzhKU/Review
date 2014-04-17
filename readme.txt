QM Calculations for Enzyme Activity Screening
---------------------------------------------
Martin Hediger
Harm Otten

Style Guide
---------------------------------------------
- Sentences on separate lines
- Spell in full abbreviations if first word of
  sentence, such as Eq./Eqs., Fig./Figs., Ref./Refs.
  or Sec./Secs.
- Italize Latin words
- Italize using \textit{}

File Guide
---------------------------------------------
000-main.tex: Main PDF output file
010-main.tex: Chapter file
999-*.tex: Backup files


Compilation
---------------------------------------------
(1) pdflatex 000-main
(2) pdflatex 000-main
(3) bibtex   000-main
(5) pdflatex 000-main
