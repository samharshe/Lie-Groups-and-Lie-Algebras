**1.**
\subsection{Mapping from Lie algebras to Lie groups via the matrix exponential function.}
\par{In the previous section we proved that $\exp$
is smooth and that $(d/dt)\exp(tX) \big |_{t=0} =
I$.}

\par{The domain of $\exp$ is $M(n)$, which we can
interpret as $\mathfrak{gl}(n)$, since
$\mathfrak{gl}(n)$ is simply $M(n)$ equipped with
the commutator bracket. Recall that the range of
$\exp$ is $GL(n)$, as demonstrated above.}

\par{The inverse function theorem states that if
$A$ is open in $\R^n$, $f: A \to \R^n$ is smooth,
and the derivative of $f$ is nonsingular at $a \in
A$, then $f$ is one-to-one from some neighborhood
$U$ of $a$ to some neighborhood $V$ of $f(a)$ and
the inverse function is also smooth (Munkres 69).}

\par{Interpreting $M(n, \R)$ as $\R^{n^2}$ and
$M(n, \C)$ as $R^{2n^2}$, by the inverse function
theorem, there exist an open neighborhood $U_0$ of
$0$ in $\mathfrak{gl}(n)$ and an open neighborhood
$V_0$ of $I$ in $GL(n)$ such that $\exp$ is a
diffeomorphism of $U_0$ onto $V_0$. The inverse of
$\exp$ on this neighborhood is, of course, $\log$.
Here part of the correspondence between Lie groups
and Lie algebras becomes visibler: $\exp$ is
a diffeomorphism from some neighborhood of the
identity of the Lie algebra to some neighborhood
of the Lie group.}

**2.**
\par{One more property of $\exp$ is needed before we can define its inverse, the matrix logarithm.}
\par{Let $X \in M(n)$. Then $\exp(tX)$ is a smooth
curve in $M(n)$ (with $t \in \C$ or $\R$), and 
\[
    \frac{d}{dt}\exp(tX) = X\exp(tX) = \exp(tX)X,
\] implying
\[
    \frac{d}{dt}\exp(tX)\Big|_{t=0} = X.
\] This follows directly from differentiating the power series term by term, which we can do inside the radius of convergence of $\exp$, which, again, is all of $M(n)$.
}

**3.**
\subsection{Regular submanifolds.}
\par{We define a useful way of establishing that a subset of a manifold is a manifold (§9 in~\cite{Tu}).}

\begin{defn}
A subset $S$ of a manifold $M$, where $\dim(M) =
n$, is a \textbf{regular submanifold of dimension
$k$} if $\forall p \in S$ there is a coordinate
chart $(U, \phi) = (U, \phi_1,\hdots,\phi_n)$ in
the atlas of $M$ such that on $U \cap S$, $\phi =
(\phi_1,\dots,\phi_k,0,\hdots,0)$: the final $n-k$
component functions of the coordinate map vanish
(reordering them if necessary). We define $\phi_S
= (\phi_1,\hdots,\phi_k)$, with $\phi_S: U \cap S
\to \R^k$. Then $(U \cap S, \phi_S)$ is a chart
for $S$ with the induced topology. We call $n-k$
the \textbf{codimension of $S$}.
\end{defn}

\begin{rmk}By this definition, $U$ is a regular submanifold of $U$ of codimension $0$.\end{rmk}

\begin{ex}Let $M = \R^2$ and $S$ be the open interval $(-1,1)$ on the $x$ axis. Taking $U = (-1,1) \times (-1,1)$ and $\phi(x,y) = (\phi_1(x,y), \phi_2(x,y)) = (x, y)$, $U \cap S$ is the zero set of $\phi_2$ on $U$, so $S$ is a regular submanifold of $\R^2$ of dimension $1$.\end{ex}

\begin{defn}
    The \textbf{level set} of a map $F$ at a point
    $c$ is subset $F^{-1}(\{c\}) = \{p \in N: F(p) =
    c\}$: the preimage of the constant $c$.
\end{defn}

\begin{defn}
    A point $c$ is a \textbf{regular value} of $F: M \to N$ if at
    each point in its level set $p \in F^{-1}(c)$ the
    differential $F^\prime_p: T_p(M) \to T_c(N)$ is
    surjective. We call the level set of $c$,
    $F^{-1}(c)$, a \textbf{regular level set}.
\end{defn}

\par{We state the following theorem, which is useful in
establishing that several classical matrix groups
are submanifolds of $GL(n)$. A proof is available
in~\cite{Tu}}

\begin{them}\label{them:rls} Regular level set theorem.
Let $F: M \to N$ a $C^\infty$ map of
manifolds, where $\dim(M) = m$ and $\dim(N) = n$.
Then for $c \in N$ a nonempty regular level set
$F^{-1}(c)$ is a regular submanifold of $M$ with
dimension $m - n$.
\end{them}

**4.**
\subsection{The four aforementioned classical matrix groups are submanifolds.}
\par{Using the regular level set theorem
(\ref{them:rls}), we show that each of the four
aforementioned classical groups are regular
submanifolds of $GL(n)$.}

\begin{them}$SL(n)$ is a regular submanifold of
$GL(n)$.\end{them}
\begin{proof}
\end{proof}

\begin{them}$\son$ is a regular submanifold of
$GL(n, \R)$.\end{them}
\begin{proof}
\end{proof}

\begin{them}$SU(n)$ is a regular submanifold of
$GL(n)$.\end{them}
\begin{proof}
\end{proof}

\begin{them}$SP(n)$ is a regular submanifold of
$GL(n)$.\end{them}
\begin{proof}
\end{proof}

\par{This completes the proof that $SL(n)$,
$\son$, $\sun$, and $SP(2n)$ are Lie groups in
sense of~\ref{def2}.}

**5.**
\begin{defn}A \textbf{Lie subalgebra} of a Lie algebra is
a vector subspace closed under the bracket.
\end{defn} 

\begin{defn}A \textbf{morphism} of Lie algebra $\mathfrak{a}$ into
Lie algebra $\mathfrak{b}$ is a $\K$-linear map
$\phi$ of $\mathfrak{a}$ into $\mathfrak{b}$ such
that 
\[
    \forall X, Y \in \mathfrak{a}, {[\phi(X),\phi(Y)]}_\mathfrak{a} = \phi({[X, Y]}_\mathfrak{b}).
\]
\end{defn}
\begin{defn}If $\phi$ is additionally one-to-one
and onto, it is a \textbf{Lie algebra
isomorphism}.\end{defn}

\begin{defn}If $\phi$ is an isomorphism of a Lie
algebra with itself, it is a \textbf{Lie algebra
automorphism}.\end{defn}

**5.**
\par{However, as the theorem suggests, there exists non-compact Lie groups that are not matrix Lie groups. We prove that one Lie group is not a matrix Lie group.}
\begin{ex}
    Weird Heisenberg group quotient thing is a Lie group but
    not a matrix Lie group.
\end{ex}
\begin{proof}
\end{proof}

**6.**
\par{We now consider a lemma that will necessary to prove the following classic non-example.}
\begin{lem}
    Let $G$ be a Lie group. Then there exists a
    non-vanishing continuous tangent vector field on $G$.
\end{lem}
\begin{proof}
    Choose an arbitrary $v \in T_e(G)$, which we
    have already established is $\g$. For any $g
    \in G$, define a left translation $\Phi_g: G
    \to G$ that sends $x \to gx$. This is a
    diffeomorphism of $G$. This induces an
    isomorphism $\phi: T_e G \to T_g G$, which maps
    $v$ to another nonzero vector $\phi_g(v) \in
    T_g(G)$. Then $\{\phi_g(v)\}$ defines a smooth
    tangent vector field on $G$, which is nonzero everywhere. 
\end{proof}
\begin{lem}
    There exists no smooth non-vanishing tangent
    vector field on $S^2$. 
\end{lem}

\begin{nex}
    Therefore, $S^2$ is not a Lie group.
\end{nex}