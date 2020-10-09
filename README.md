# Papers Tikz package
[![GitHub license](https://img.shields.io/badge/license-LLPL--1.3c-blue)](https://github.com/bThink-BGU/Papers-Latex-BP-Tikz/blob/master/LICENSE)
![GitHub release](https://img.shields.io/github/release/bThink-BGU/Papers-Latex-BP-Listings)

Latex package based on TikZ for adding BPjs shapes to your paper

Current release includes pictures for the BP life cycle and COBP life cycle.

This project is licensed under the LaTeX Project Public License v1.3c or later, see http://www.latex-project.org/lppl.txt

## 1. Behaviroal Programming (BP)
Behavioral Programming (BP) is a novel, language-independent paradigm for programming reactive systems, centered on natural and incremental specification of behavior.

For more information visit [here](https://m-cacm.acm.org/magazines/2012/7/151241-behavioral-programming/fulltext).

[BPjs](https://github.com/bThink-BGU/BPjs) is an environment for running behavioral programs written in Javascript.

## 2. Installation
Add the [pgf-bp.sty](pgf-bp.sty) file to your Latex project.

In [Overleaf](https://www.overleaf.com/) this can be done by:
1. Adding a new file to the repository.
1. Selecting "From External URL".
1. In the first textbox write https://raw.githubusercontent.com/bThink-BGU/Papers-Latex-BP-Listings/master/pgf-bp.sty
1. Press "Create".

## 3. Usage
### 3.1. Loading the package
Load the package with 
```latex
\usepackage{tikz}
\usepackage{pgf-bp}
```

### 3.2 Usage Examples
```latex
\documentclass{standalone}
\usepackage{tikz}
\usepackage{pgf-bp}

\begin{document}
  \begin{tikzpicture}
    \pic {bpcycle};
  \end{tikzpicture}
  
  \begin{tikzpicture}
    \pic {cobpcycle};
  \end{tikzpicture}	
\end{document}
```
