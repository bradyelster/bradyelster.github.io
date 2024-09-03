+++
title = "On Christoffel Symbols"
hascode = true
rss = "How Christoffel symbols can be a powerful tool in physics. Last updated: Setpember 2, 2024"
rss_title = "On Christoffel Symbols"
rss_pubdate = Date(2024, 9, 2)

tags = ["geometry", "tensors", "christoffel"]
+++

\toc

# On Christoffel Symbols

You may have never heard of them before, but the Christoffel symbols are fundamental in tensor calculus and generally important whenever one works with an abstract surface or coordinate system. Let's begin with an easy example of where they show up. 

![image](/assets/images/christoffel_blackongrey.png)

## Polar Coordinates

## Geodesic Curves
A more advanced example of where the Christoffel symbols show up is in finding geodesic curves: the "straightest possible path between points on a surface". I show [here]() that all geodesics in Cartesian coordinates are straight lines. But in other coordinate systems, they are harder to compute. 

The Christoffel symbols can be computed once elements of the inverse metric tensor are known. Then you multiply those by derivatives of your basis vectors $\frac{\partial\vec{R}}{\partial u^{i}} \equiv \vec{e}_{i}$

\begin{equation}
    \Gamma_{ij}^{k} = \frac{\partial^{2}{\vec{R}}}{\partial{u}^{i} \partial{u}^{j}} \frac{\partial{\vec{R}}}{\partial{u}^{l}} \mathfrak{g}^{lk} \pderiv[1]{f}{x}
\end{equation}