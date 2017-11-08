# TwitterTraumaBBD2017

*__Note__ that the interactive plots displayed in this slide deck may not render well (if at all) in Firefox. Chrome and Safari appear to be unaffected by this issue (though this has not been thoroughly tested). YMMV.*

This repository contains a slide deck entitled "Twitter-based Alerts of Major Disasters," which was presented in UC Berkeley's Biomedical Big Data seminar on 13 November 2017.  The deck was built using the [R](http://www.r-project.org/) package [xaringan](https://github.com/yihui/xaringan), with support from [knitr](http://cran.r-project.org/web/packages/knitr/index.html), [R Markdown](https://rmarkdown.rstudio.com), and [pandoc](http://johnmacfarlane.net/pandoc/).

The file for the main deck is [index.html](https://saraemoore.github.io/TwitterTraumaBBD2017/index.html), built from the [RMarkdown](http://rmarkdown.rstudio.com/) file [index.Rmd](https://github.com/saraemoore/TwitterTraumaBBD2017/blob/master/index.Rmd). To recompile **in R**:

```
# install.packages("rmarkdown")
library(rmarkdown)
render("index.Rmd")
browseURL("index.html")
```

