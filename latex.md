# LaTeX Documentation

## 1. Introduction to LaTeX

### What is LaTeX?

LaTeX is a document preparation system based on the TeX typesetting system. It is widely used to create professional documents, academic papers, reports and books.

### Why LaTeX?

- Free and portable.
- Provides professionally designed layouts.
- Makes mathematical typesetting convenient.
- Supports multiple output formats.
- Automatically handles references, footnotes, tables of contents and bibliographies.

### LaTeX Tools

LaTeX can be used through offline and online tools.

| Offline Tools | Online Tools |
|---|---|
| MiKTeX | Overleaf |
| TeX Live | Papeeria |
| TeXstudio | CoCalc |

### Input and Output

A LaTeX source file is a plain text file saved with the `.tex` extension. It contains document text along with LaTeX commands.

Common output formats include:

- PDF (`.pdf`)
- DVI (`.dvi`)
- PostScript (`.ps`)
- Rich Text Format (`.rtf`)

## 2. Basic Document Structure

Every LaTeX document contains three main components:

```latex
\documentclass{article}

\begin{document}

This is my first LaTeX document.

\end{document}
```

### Explanation

- `\documentclass{article}` – Defines the type of document.
- `\begin{document}` – Marks the beginning of the document content.
- `\end{document}` – Marks the end of the document.

### Document Classes

The `\documentclass` command specifies the overall structure of a document.

| Class | Purpose |
|---|---|
| `article` | Short documents and research papers |
| `report` | Reports and longer documents |
| `letter` | Formal letters |

### Document Class Options

Optional settings can be added inside square brackets.

Example:

```latex
\documentclass[12pt,a4paper]{article}
```

- `12pt` specifies the font size.
- `a4paper` specifies the paper size.
- `article` specifies the document class.

## 3. Adding Title, Author and Date

LaTeX provides commands to add a title, author name and date to a document.

### Important Commands

- `\title{}` – Defines the title of the document.
- `\author{}` – Specifies the author's name.
- `\date{}` – Specifies the date.
- `\maketitle` – Displays the title, author and date.

### Important Points

- The title, author and date are defined before `\begin{document}`.
- The `\maketitle` command must be placed after `\begin{document}`.
- `\today` displays the current date automatically.

## 4. Comments and Page Styles

### Comments in LaTeX

Comments are used to add notes in the source code. They do not appear in the compiled document.

The `%` symbol is used to create comments.

Example:

```latex
\documentclass{article}

\begin{document}

This text is processed.

% This is a comment.
This text is also processed.

\end{document}

When LaTeX encounters `%`, it ignores the remaining part of that line.

## 5. Hyphenation

LaTeX automatically hyphenates words when necessary to format text properly.

The `\-` command specifies possible points where a word can be divided.

Example:

```latex
manu\-script
data\-base
micro\-processor
```

The word is divided only when a line break occurs at the specified position.

## 5. Font Sizes

LaTeX provides predefined commands to change the font size.

| Command | Font Size |
|---|---|
| `\tiny` | Tiny |
| `\small` | Small |
| `\normalsize` | Normal |
| `\large` | Large |
| `\Large` | Larger |
| `\LARGE` | Very large |
| `\huge` | Huge |
| `\Huge` | Largest |

The font size command affects the text enclosed within its braces.

## 6. Text Alignment

LaTeX provides three environments for aligning text:

- `flushleft` – Aligns text to the left.
- `center` – Aligns text to the center.
- `flushright` – Aligns text to the right.

## 7. Lists in LaTeX

LaTeX provides three types of lists:

- `itemize` – Creates a bulleted list.
- `enumerate` – Creates a numbered list.
- `description` – Creates a list with descriptions.

## 8. Trivlist Environment

The `trivlist` environment creates a simple list without bullets or numbers.

Example:

```latex
\begin{trivlist}
\item First item without label
\item Second item
\end{trivlist}
```

Each `\item` adds a new item to the list.
