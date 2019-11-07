# Digital Scholarship Studio Spring 2020 Workshop

This repo builds on the [r binder](https://github.com/binder-examples/r) and [jupyter lab binder](https://github.com/binder-examples/jupyterlab) and is complementary to the [multi-language-demo binder](https://github.com/binder-examples/multi-language-demo) with examples on using both R and python in both Jupyter Lab and RStudio.

 - Launch in Jupyter Lab: [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/binder-examples/r_with_python/master?urlpath=lab)
 - Launch in RStudio: [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/binder-examples/r_with_python/master?urlpath=rstudio)

Example files included:

 - `python_example_for_Jupyter.ipynb` - Notebook file using a python kernel for working in Jupyter
 - `R_example_for_Jupyter.ipynb` - Notebook file using an R kernel for working in Jupyter
 - `python_example_for_RStudio.Rmd` - RMarkdown file with python code chunks for working in RStudio
 - `R_example_for_RStudio.Rmd` - RMarkdown file with R code chunkcs for working in RStudio

Note: to mix R and python in a single Jupyter notebook, use cell magic as demonstrated in the [multi-language-demo](https://github.com/binder-examples/multi-language-demo) binder examples. To mix R and python in a single RMarkdown file (and exchange information between them), make use of [reticulate](https://rstudio.github.io/reticulate/). The latter requires [RStudio 1.2+](https://www.rstudio.com/products/rstudio/download/preview/) to work interactively, which is not yet installed as the default binder version (i.e. interactive python and python plots will not yet work in RMarkdown and the above example file uses reticulate for plotting in the knitted file).

## Start

To begin, click on the "Launch Binder" button above. It will redirect you to an active instance of Jupyter Notebooks, where we'll complete these excercises. 

