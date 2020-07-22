--- 
title: "A Minimal Book Example"
author: "Yihui Xie"
date: "2020-07-22"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: jennybc/apple
description: "This is a minimal example of using the bookdown package to write a book. The output format for this example is bookdown::gitbook."
---

# Prerequisites

Bacon ipsum dolor amet pork belly porchetta andouille pig, tri-tip beef ribs alcatra kielbasa shankle. Corned beef short ribs ground round, picanha kielbasa sausage meatloaf rump fatback prosciutto. Cow jerky ground round rump flank doner. Porchetta turkey chuck chicken alcatra. Tongue boudin short ribs hamburger short loin pork drumstick doner tail pork chop ground round tenderloin kielbasa frankfurter. Prosciutto porchetta andouille beef ribs tri-tip jowl venison cow tongue meatball.

Tail ham tenderloin frankfurter. Shank andouille strip steak salami tongue brisket short ribs corned beef fatback pork chop turducken meatball boudin cow. Picanha tongue filet mignon biltong short loin shankle. Cupim biltong frankfurter andouille, beef ribs leberkas doner meatloaf strip steak short loin shoulder ham hock flank. Turducken chislic pig pork spare ribs beef ribs flank pancetta sausage kevin turkey buffalo.

Capicola turkey shank pork loin, tri-tip prosciutto meatloaf pancetta shoulder beef rump chuck landjaeger ball tip ham hock. Short ribs prosciutto kevin, cow spare ribs tail hamburger brisket shank turducken beef corned beef flank. Short ribs salami pork cupim beef pork belly frankfurter jerky, porchetta short loin prosciutto beef ribs pork chop ball tip. 

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$.

The **bookdown** package can be installed from CRAN or Github:


```r
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```

Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.name/tinytex/>.

