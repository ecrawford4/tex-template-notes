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

This repository contains the LaTeX template I use to take notes in school. It is based off of a public book format: 

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

Here is the output of these three examples:

[output](assets/output.png)
