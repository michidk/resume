![Build LaTeX](https://github.com/michidk/resume/workflows/Build%20LaTeX%20document/badge.svg)

# Résumé

My personal résumé and curriculum vitae.

## Prerequisites

Dependencies are Texlive-Full and latexmk.

## Building

To build the .pdf-file, execute:
`latexmk -interaction=nonstopmode -file-line-error -xelatex $(FILE)`
