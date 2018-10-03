### How to write scribe notes

So that we don't have to go back and correct your scribe notes for style, follow the following rules:

1. To start a new lecture $n$, create a folder $n$ and scribe in $n$.tex. You can look at the sample Lecture 1 for reference. 
2. Start your scribe with a 3-4 lines summary of what is going on in today's lecture.
3. Don't use `\section`, use `\subsection` instead.  Don't indent your text for `\subsection`. Indent for `\begin\{itemize\}` or `begin\{enumerate\}` environments.
4. Do not end lines with the `\\` command. Instead, start different lines of the same paragraph on a fresh line. Insert a blank line between consecutive paragraphs.
5. Use `\on{}` for text that refers to symbols, like `\on{NP}` (displayed as: $\operatorname{NP}$). Use `\mcD` (displayed as: $\mathcal{D}$) for distribution and so on. 
6. Always use `\log` instead of log, and similarly for other functions (sin, cos, etc.). We've defined a `\exp`, though it's not standard.

#### Images
*All* images should be encased in a `\figure` environment. Include a descriptive caption and a label. Refer to them from the text using the label. Center the image.

#### Exercises
Use the `\begin{exercise} ... \end{exercise}`. Use `\begin{proof} ... \end{proof}` for the solution.
