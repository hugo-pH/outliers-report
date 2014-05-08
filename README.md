outliers-report
===============

With the aim of detect [outliers values](http://en.wikipedia.org/wiki/Outlier) and create a dynamic report informing about them, here are two [knitr](http://yihui.name/knitr/) files which can perform this task.
The outliers_report.Rnw is the main document, where functions are defined and data is processed. This script calls a child file, outliers_loop.Rnw, where outliers values are printed and ploted recursively. 

* Data should be provided as a data.frame and saved as 'outvals.data' in the same working directory. 



Thanks to Yihui Xie for developing the greatful knitr package and also to the R developer's team. 

 R Core Team (2013). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL http://www.R-project.org/.


