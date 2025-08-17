+++
title = "Root-Finding"
hascode = true
rss = "Notes on Root-Finding. Last updated: Jan 23, 2025"
rss_title = "Root-Finding"
rss_pubdate = Date(2025, 1, 23)

tags = ["numerical methods"]
+++

# Root-Finding Problems
\begin{aligned}
    f(x) = 0
\end{aligned}

## Bisection Method

## Regula Falsi (False Position)

## Newton's Method

# Order of Convergence
Let $r$ be the root of our function and $x_{n}$ be the $n$-th approximation ot the root. Then we define the error as
$$
\begin{equation}
\epsilon_{n} = r - x_{n}.
\end{equation}
$$

For large $n$ we assume the approximate relatonship
$$
\begin{equation}
|\epsilon_{n+1}| = k |\epsilon_{n}|^{p}
\end{equation}
$$