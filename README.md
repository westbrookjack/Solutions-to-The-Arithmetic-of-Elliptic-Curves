# Solutions to *The Arithmetic of Elliptic Curves*

This repository contains expanded notes and fully worked solutions to exercises from  
**_The Arithmetic of Elliptic Curves_** by Joseph H. Silverman (2nd Edition).

## ✨ Features

- Expanded and clarified **theorems**, **proofs**, and **remarks**
- Fully worked **solutions** to exercises
- Clean LaTeX formatting for readability and reuse
- Organized by chapter, with internal referencing and optional bibliography support

## 📁 Files

- `main.tex` – The primary LaTeX file (includes all chapters and content)
- `references.bib` – Bibliography file (optional, used for citing references)

## 🛠 Compilation Instructions

To compile locally:

```bash
pdflatex main.tex
bibtex main       # Skip if you don't use citations
pdflatex main.tex
pdflatex main.tex
