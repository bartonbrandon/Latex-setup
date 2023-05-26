# Latex-setup
My personal latex setup for research and notes. This configuration is set up for research specifically in mathematics and theoretical physics.


# What you need
## Neovim and vim-plug
Being at leat somewhat comfortable with neovim is a prerequisite to installing anything below. You should understand how to use .config/init.vim, as you will need this for vim-tex.

## Vim-tex
https://github.com/lervag/vimtex

https://www.ejmastnak.com/tutorials/vim-latex/intro/

## Pdf viewer
A pdf viewer is essential if you would like to read your document. Zathura is what I use, because it compiles in the background continuously with vim-tex.
https://github.com/dracula/zathura

## Latex compiler
You will need a latex compiler. I am using latexmk which works well with vim-tex.
https://mg.readthedocs.io/latexmk.html

## Latex
You will need to install latex on your machine. I am using TexLive, which you can install using the instructions in the documentation below. Note: You will need to add the local versions to your path, so vim-tex will recoginize them (see stackexchange post below).

https://www.tug.org/texlive/quickinstall.html

https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path

https://tug.org/texlive/doc.html

http://tug.ctan.org/info/tlmgrbasics/doc/tlmgr.pdf

### Inspired by
https://github.com/SeniorMars/dotfiles

https://github.com/gillescastel
