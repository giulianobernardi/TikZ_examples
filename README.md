# TikZ_examples

This is a collection of TikZ files that I either generated or borrowed from other members of the DSP Group in ESAT (KUL, Belgium).

Most of the TikZ files have a corresponding generated pdf file (with the same name).

One should be able to compile the TikZ files within the LaTeX document in `main_tikz.tex`, which makes use of other macros stored in `common_files`.

On MacOS, to visualize the single TikZ files I use the following software: 
- [Sublime Text 3](https://www.sublimetext.com/3) as Text editor
- [Skim](https://skim-app.sourceforge.io/) as a light PDF viewer

And set them up as follows:

## Setup Sublime Text 3 (ST3)
1. Install ST3
2. Install the ST3 package `Latexing` from the ST3 Package control (invoke by pressing `Command`+`Shift`+`B`)
3. Install the ST3 package `TikZ` from the ST3 Package control (invoke by pressing `Command`+`Shift`+`B`)
4. Add the lines ```"tikz": true, "tikz_create_pdf": true``` 
to `Sublime Text/Settings.../Package Settings/LaTeXing/Settings - User `

## Setup Skim
1. Install Skim
2. Configure it to work on ST3

## Setup your TikZ files
The string 
```
% -*- root: main_tikz.tex -*-
``` 
must be added to the TikZ file, where `main_tikz.tex` is the name of the main file included in the repo containing the preamble. You can use differen main files
