<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Brady Elster"
mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
prepath = ""

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
# generate_rss = true
# website_title = "Brady's Website"
# website_descr = "Brady's Website using Franklin"
# website_url   = "https://bradyelster.github.io/blog"
+++

<!--
Add here global LaTeX commands to use throughout your pages.
-->

<!--commands-->
<!--unit vectors-->
\newcommand{\ihat}{\textbf{\^\i}}
\newcommand{\jhat}{\textbf{\^\j}}
\newcommand{\rhat}{\bm{\hat{r}}}
\newcommand{\zhat}{\bm{\hat{z}}}
\newcommand{\yhat}{\bm{\hat{y}}}
\newcommand{\xhat}{\bm{\hat{x}}}
<!--misc-->
\newcommand{\phihat}{\bm{\hat{\vp}}}
\newcommand{\bb}[1]{\mathbb{#1}}
\newcommand{\grad}{\bm{\nabla}}
\newcommand{\vp}{\varphi}
\newcommand{\F}{F^{*}}
\newcommand{\ff}[1]{{\color{RoyalBlue}{#1}}}
\newcommand{\ellip}{\bm{\Delta^*}}
\newcommand{\ex}{\text{i.e.}}
\newcommand{\uj}{\bm{u}_j}
\newcommand{\abs}[1]{\left|#1\right|}
<!--custom fit parenthesis-->
\newcommand{\LL}{\left( }
\newcommand{\RR}{\right) }
<!--derivatives-->
\newcommand{\pderiv}[3][]{% \deriv[<order>]{<func>}{<var>}
  \ensuremath{\frac{\partial^{#1} {#2}}{\partial {#3}^{#1}}}}
\newcommand{\tderiv}[3][]{% \deriv[<order>]{<func>}{<var>}
  \ensuremath{\frac{d^{#1} {#2}}{d {#3}^{#1}}}}\newcommand{\grad}{\vec{\nabla}}
