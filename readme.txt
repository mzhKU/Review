QM Calculations for Enzyme Activity Screening
---------------------------------------------
Martin Hediger

Style Guide (recommended)
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
999-*.tex   : Backup files
040-*.*     : Figures
pages.txt:  : Links collection file

Compilation
---------------------------------------------
(1) pdflatex 000-main
(2) pdflatex 000-main
(3) bibtex   000-main
(5) pdflatex 000-main

Useful git commands
---------------------------------------------
Check if pull required:
git fetch -v --dry-run
git remote -v update

Check commits which are not yet pushed to remote:
git log --branches --not --remotes

Only most recent:
git log --branches --not --remotes --simplify-by-decoration --decorate --oneline

PYMOL Commands for ray tracing
---------------------------------------------
See: http://cupnet.net/ambient-occlusion-pymol/
fetch 1BTA
set_color oxygen, [1.0,0.4,0.4]
set_color nitrogen, [0.5,0.5,1.0]
remove solvent
as spheres
util.cbaw
bg white
set light_count,10
set spec_count,1
set shininess, 10
set specular, 0.25
set ambient,0
set direct,0
set reflect,1.5
set ray_shadow_decay_factor, 0.1
set ray_shadow_decay_range, 2
unset depth_cue
ray 1200, 1200

Notes 30.05.14
---------------------------------------------
Conclusions:
Outlook? Summary? How to evolve the field?
And when we look back at the two companies from the beginning?
Requirements: Structure (only) required if *this* method should be used.
