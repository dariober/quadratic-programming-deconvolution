## A tutorial on quadratic programming applied to the deconvolution of mixed cell populations

In a nutshell, this tutorial ([pdf](quadratic_programming_tutorial.pdf)) shows
how to use quadratic programming, as implemented in the R packages
[pracma](https://CRAN.R-project.org/package=pracma) and
[quadprog](https://CRAN.R-project.org/package=quadprog), to solve the
problem of deconvolving a mixed cell population into individual subpopulations.

[Quadratic programming](https://en.wikipedia.org/wiki/Quadratic_programming)
solves the problem of optimizing (minimizing or maximizing) a quadratic
function of several variables subject to linear constraints on these variables.  
Among many other applications, it can be used to deconvolve a mixed population
of cells into individual subpopulations given, for example, the expression
profile of the mixed population and the reference profiles of the single subpopulations
(_e.g._ [Cobos et al.
2018](https://academic.oup.com/bioinformatics/article/34/11/1969/4813737)).

Quadratic programming has been implemented in various languages including R and
python. However, I found the documentation and examples quite abstract and difficult to 
apply to real problems.

I wrote this document for my own reference and hopefully to be useful to
others, but it is not meant to be authoritative in any way. Feel free to open
an issue to send any comment, question, or correction. 

-----

To Compile the pdf document execute:

```
cd latex
pdflatex quadratic_programming_tutorial.tex
mv quadratic_programming_tutorial.pdf ../
```
