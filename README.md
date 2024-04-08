\documentclass{article}

\usepackage{hyperref}
\usepackage{geometry}
\usepackage{listings}
\geometry{a4paper, margin=1in}

\title{README: Basic Writing and Formatting Syntax for GitHub Markdown}
\author{}
\date{}

\begin{document}

\maketitle

\section*{Headings}

To create a heading, add one to six \# symbols before your heading text. The number of \# you use will determine the size of the heading.

\begin{lstlisting}
# The largest heading
## The second largest heading
###### The smallest heading
\end{lstlisting}

\section*{Styling Text}

You can indicate emphasis with bold, italic, or strikethrough text.

\begin{itemize}
    \item \textbf{Bold}: \textbf{**Bold**}
    \item \textit{Italic}: \textit{*Italic*}
    \item \sout{Strikethrough}: \sout{~~Strikethrough~~}
\end{itemize}

\section*{Quoting Text}

You can quote text with a \textgreater{}.

\begin{lstlisting}
> Quoted text
\end{lstlisting}

\section*{Quoting Code}

You can call out code or a command within a sentence with single backticks (\`). The text within the backticks will not be formatted.

\begin{lstlisting}
Use `git status` to list all new or modified files that haven't yet been committed.
\end{lstlisting}

To format code or text into its own distinct block, use triple backticks (\`\`\`).

\begin{lstlisting}
