To build website and serve locally:


```sh
source .secret && Rscript _preprocess.R && Rscript  -e 'blogdown::build_site(build_rmd = TRUE)' &&  Rscript -e  'blogdown::serve_site()'
```
