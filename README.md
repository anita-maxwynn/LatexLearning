# LatexLearning
## Day 1 - LaTeX Practice

This folder contains my first day of practice with LaTeX.  
I explored the basics of document structure, text formatting, and simple mathematical expressions.

### Contents
- Basic document setup with `\documentclass` and `\begin{document}`
- Using special commands like `\LaTeX`
- Line breaks and comments
- Inline and display math mode examples
- Superscripts and subscripts usage

### Files
- `first1.tex` — A basic introduction to LaTeX syntax
- `second1.tex` — Practice with math expressions
- `third3.tex` — More complex math notations and formatting

### How to compile
Run the following command to generate a PDF from a `.tex` file:

```bash
pdflatex filename.tex
```



---


## Day 2 - LaTeX Learning

This marks my second day of learning LaTeX.  
Today, I practiced various formatting commands, learned about document structuring, created macros, added images, and learned how to debug LaTeX errors.

---

### ✅ What I Learned

#### 📝 Text Formatting
- `\textit{}` – *Italic*
- `\textbf{}` – **Bold**
- `\textsc{}` – SMALL CAPS
- `\texttt{}` – `Typewriter (Monospace)`
- `\href{url}{text}` – Hyperlinked text using `hyperref` package

#### 🔡 Font Sizes
- `\begin{large}...\end{large}`
- `\begin{Large}...\end{Large}`
- `\begin{huge}...\end{huge}`
- `\begin{Huge}...\end{Huge}`
- `\begin{small}...\end{small}`
- `\begin{scriptsize}...\end{scriptsize}`
- `\begin{tiny}...\end{tiny}`

#### 🧭 Text Alignment
- `\begin{center}...\end{center}`
- `\begin{flushleft}...\end{flushleft}`
- `\begin{flushright}...\end{flushright}`

#### 🧾 Sections
- `\section{}`, `\subsection{}` for organizing content

#### 📦 Packages Used
- `hyperref` – for clickable links
- `amsmath, amssymb, amsfonts` – for advanced math formatting
- `graphicx` – to include images
- `float` – to force image placement using `[H]`

---

### ✨ Macros
Defined custom LaTeX macros using `\def`.  
Example:
```latex
\def \eq1{y=\dfrac{x}{3x^2+x+1}}
````

Used this as:

```latex
$\eq1$
```

---

### 🖼️ Inserting Images

Learned how to add images with a caption:

```latex
\begin{figure}[H]
\includegraphics[scale=0.5]{Beako_Reading_The_TypeScript_Programming_Language}
\caption{this is caption}
\end{figure}
```

---

### 🚨 Errors & Debugging

* Learned to interpret `.log` file errors
* Fixed issues like:

  * Unescaped backslashes
  * Mismatched `\begin` / `\end`
  * Compilation issues with missing packages
* Used `%` for comments to disable lines temporarily
* Discovered that **Texmaker's Quick Build** is super useful for debugging quickly

---

### 🗂️ Files Created

* `day2_formatting.tex`
* `day2_macros_figures.tex`

---

## 🧠 Command Used to Compile

```bash
pdflatex filename.tex
```

---

🖋️ Authored by **Anita Max-Wynn**

