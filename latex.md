# LaTeX Documentation

## 1. Introduction to LaTeX
### What is LaTeX?
LaTeX is a document preparation system based on the TeX typesetting system.

## 2. Basic Document Structure
Every LaTeX document contains three main components:

```latex
\documentclass{article}
\begin{document}
This is my first LaTeX document.
\end{document}

## 3. Adding Title, Author and Date
LaTeX provides commands to add a title, author name and date to a document.

### Important Commands
- `\title{}` – Defines the title of the document.
- `\author{}` – Specifies the author's name.
- `\date{}` – Specifies the date.
- `\maketitle` – Displays the title, author and date.

### Example
```latex
\documentclass{article}
\title{Hello, World! In LaTeX}
\author{Manish}
\date{11 November 2026}
\begin{document}
\maketitle
Hello, World!
\end{document}
