# LEPL2990-Manuscript
This repository hosts my master thesis manuscript.

The last compiled version of the document can be found [here](https://github.com/geverartsdev/LEPL2990-Manuscript/blob/master/manuscript.pdf).

### Dependencies
#### Ubuntu
```console
$ apt install texlive texlive-lang-english texlive-latex-extra
```

### Compile document
The base source document is [manuscript.tex](https://github.com/geverartsdev/LEPL2990-Manuscript/blob/master/manuscript.tex).  
The output file is [manuscript.pdf](https://github.com/geverartsdev/LEPL2990-Manuscript/blob/master/manuscript.pdf).


To compile the document, simply run this command in the project's directory.
```bash
latexmk -pdf manuscript.tex
```

:bulb: **Tips:** Activate watching of updated files by adding `-pvc` to the command.

### Author
Guillaume Everarts de Velp

### License
