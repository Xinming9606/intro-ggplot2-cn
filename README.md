# ggplot2 book

这是 [ggplot2-book](https://github.com/hadley/ggplot2-book) 的中文翻译项目。翻译约定详见 [[conventions]]

This is a fork of [ggplot2-book](https://github.com/hadley/ggplot2-book). The project is to build a chinese version of this wonderful book for education.

<!-- badges: start -->
[![Build status](https://github.com/hadley/ggplot2-book/workflows/workflow/badge.svg)](https://github.com/hadley/ggplot2-book/actions)
<!-- badges: end -->

This is code and text behind the [ggplot2: elegant graphics for data analysis](http://ggplot2-book.org/) book. Please help us make it better by [contributing](contributing.md)!

## Installing dependencies

Install the R packages used by the book with:

```r
# install.packages("devtools")
devtools::install_deps()
```

## Build the book

In RStudio, press Cmd/Ctrl + Shift + B. Or run:

```R
bookdown::render_book("index.Rmd")
```
