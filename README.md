# bfscp_slides
Latex/Beamer code for slides used in [bfs(competitive_programming)](https://code-drills.com/bfscp) lectures.

# Compiling
Requires following softwares and libraries:

* pdflatex
* beamer (Latex library)
* minted (latex library)
* Pygmentize (python software)

```
pdflatex -shell-escape intro1.tex
```

It will ask for a file name twice. Enter any name as it is for a temperory file (we use i as gitignore is setup to ignore i.tex).
A pdf file intro1.pdf should appear in the same directory. 
