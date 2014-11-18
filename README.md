rmarkdown: Alter Action Depending on Document
===========================

This repo is designed to accompany [this blog post](http://trinkerrstuff.wordpress.com/2014/11/18/rmarkdown-alter-action-depending-on-document/) that explains how to accomplish this wish:

> "I wish I could do X for document type A and Y for document type B"

This repo contains:

- 2 Rmd documents   
  - **simple.Rmd**: A simple MWE    
  - **extended.Rmd**: An extended Example     
- **preambleish.sty** to accompany *extended.Rmd*        
- **render.R** to render .html, .pdf, and .docs documents from the .Rmd files  

You can fork this repo, install locally, and then run:


```r
rmarkdown::render("simple.Rmd", "all")

rmarkdown::render("extended.Rmd", "all")
```

...to render the documents.


