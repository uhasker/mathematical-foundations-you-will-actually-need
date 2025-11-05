# Mathematical Foundations You Will Actually Need

## Status

This book is still work in progress.

## Compiling the PDF

You will need a LaTeX distribution.
The simplest way to get one on a Debian-based system is:

```sh
sudo apt update
sudo apt install texlive-full
```

Install the pygments package:

```sh
python -m pip install pygments
```

Then compile the .tex file:

```sh
pdflatex -shell-escape book.tex
```
