# textemplate-notes

To automatically compile LaTeX in Codespaces, install 
the following extensions:

[![James-Yu.latex-workshop](assets/image.png)](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

and run:

```sh
sudo apt update
sudo apt install texlive texlive-latex-extra latexmk
```

## Statement of Purpose

This repository contains the LaTeX template I use to take notes in school. It is based off the Tufte-Style Book. More information about the template can be found below


I added three custom environments: one for examples

```LaTeX
\begin{example}[Example Title]
    sample text
\end{example}
```

one for definitions

```LaTeX
\begin{definition}[Definition Title]
    sample text
\end{definition}
```

and one for code:

```LaTeX
\begin{codeblock}[Code Title]
\begin{lstlisting}
sample code{
    sample.method(sample.getData);
}
\end{lstlisting}
\end{codeblock}
```

Here is the output of these three environments:

![output](assets/output.png)


## Tufte-Style Book (Minimal Template)

> LaTeX Template

> Version 1.0 (5/1/13)

> This template has been downloaded from: http://www.LaTeXTemplates.com

> License: CC BY-NC-SA 3.0 (http://creativecommons.org/licenses/by-nc-sa/3.0/)

### IMPORTANT NOTE:

In addition to running BibTeX to compile the reference list from the .bib
file, you will need to run MakeIndex to compile the index at the end of the
document.
