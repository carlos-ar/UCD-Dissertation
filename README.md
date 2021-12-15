# UCD-Dissertation-Template
2021 Dissertation template modified from the [Galois Group template](https://galois.math.ucdavis.edu/doku.php?id=thesistips). I do not take credit for any of the hard work by all the individuals who worked on such a useful dissertation template. I thank them for their work.

Some notes

1. I used the `book` document class instead of the `amsbook` class to have more control over the section titles using `titlesec` and `titletoc`. I do not have enough experience with either to make them work together.

2. The modifications to the original template are fairly minor, as there is only two changes in the `LayoutPreamble.tex` file that I changed. 

3. All major modifications exist in the `MacrosPreamble.tex` file which is fairly documented in rational. In this file you will find all the extra packages, which are fairly standard in my experience.

4. This template includes my actual abstract for my dissertation, as seen in ProQuest.

5. I've used several tools to [generate tables](https://www.tablesgenerator.com/) and [tikz](https://www.mathcha.io/editor) diagrams. 

6. I work in [Sublime Text](https://www.sublimetext.com/), and have the `LatexTools` package installed to make it all work together. Therefore, you have some directives at the top of documents `%!TEX root = ../Dissertation.tex` and `%!TEX program = xelatex` since these tell Sublime 

   1. where we are relative to the directory structure
   2. which compiler to use for the document

   I did this because I used `xelatex` for a project a long time ago, and I can't remember why. Anyway, it works using `pdflatex` as well. 
