

# Problem 4.20, Claim: The problem of determining whether a DFA and a regular expression are equivalent is decidable.

\begin{proof}
  Let $M$ be a DFA and $R$ be a regular expression. Define the language $C = \{\langle M, R \rangle \mid M \text{ is a DFA and } R \text{ a regular expression with} L(M) = L(R)\}$.
  \newline
  Sipser defines a Turing machine $F$ that decides $C$. Thus, the claim holds.
\end{proof}


# Problem 4.26: Answer the following for the given functions.

\begin{enumerate}[label=(\alph*)]
\item \textbf{Is $f$ one-to-one?} \\
  \newline
  No, each of 6 and 7 in $Y$ are mapped to multiple values in $X$.
\item \textbf{Is $f$ onto?} \\
  \newline
  No, each of 8, 9, and 10 in $Y$ are not mapped to any input in $X$.
\item \textbf{Is $f$ a correspondence?} \\
  \newline
  Yes; each input maps to a single output, thus it is well-defined.
\item \textbf{Is $g$ one-to-one?} \\
  \newline
  Yes; $g$ satisfies $g(a) = g(b)$ iff $a = b$, for all $a, b \in X$.
\item \textbf{Is $g$ onto?} \\
  \newline
  Yes; each $y \in Y$ has $x \in X$ s.t. $g(x) = y$.
\item \textbf{Is $g$ a correspondence?} \\
  \newline
  Yes; since $g$ is a bijection, it must be well-defined.
\end{enumerate}

