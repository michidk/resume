# Curriculum Vitae

![Build LaTeX](https://github.com/michidk/resume/workflows/Build%20LaTeX%20document/badge.svg)

My personal résumé and curriculum vitae

## Prerequisites

Dependencies are Texlive-Full and latexmk.

## Building

To build the .pdf-file, execute:
`latexmk -interaction=nonstopmode -file-line-error -xelatex $(FILE)`

## Types

The following resume types are available:

| Type              | Filename             | Explanation                 |
| ----------------- | -------------------- | --------------------------- |
| Curriculum Vitae  | `cv.tex`             | My whole career path        |
| CV (EU Version)   | `cv-eu.tex`          | My CV including a mugshot   |
| Résumé            | `resume.tex`         | A two page summary of my CV |
| Résumé (One Page) | `resume-onepage.tex` | A one page summary of my CV |
