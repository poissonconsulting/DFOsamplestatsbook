<!-- badges: start -->
![bookdown](https://github.com/poissonconsulting/DFOsamplestatsbook/workflows/bookdown/badge.svg)
<!-- badges: end -->

# Introduction 

This booklet provides the course material for the DFO sampling statistics course provided by [Poisson Consulting](https://www.poissonconsulting.ca). 

It is also available as a website from:

https://poisson-dfosamplestatsbook.netlify.app

password: salmonids

## Instructions

### Update

To update the website simply push to GitHub.

### Service

To serve locally:
```r
bookdown::serve_book()
```

To build an epub book:
```r
bookdown::render_book("index.Rmd", "bookdown::epub_book")
```

To build a pdf book:
```r
bookdown::render_book("index.Rmd", "bookdown::pdf_book")
```
