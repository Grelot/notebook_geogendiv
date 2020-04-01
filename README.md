# notebook_geogendiv
A jupyter notebook work using R-package geogendiv


# Installation 

## R with jupyter notebook in linux

R 3.6 

https://marcocarnini.github.io/software/2016/08/01/installing-r-kernel-for-jupyter.html

```
apt-get install r-base r-base-dev libssl-dev libcurl3-dev curl libxml2-dev
```

The installation of the R kernel for Jupyter is performed under R command line (as from the GitHub page of the project, https://github.com/IRkernel/IRkernel):

```
install.packages(c('pbdZMQ', 'repr', 'devtools')) 
devtools::install_github('IRkernel/IRkernel') 
IRkernel::installspec()
```
## R packages

see [INSTALL.R](INSTALL.R)


## conda environment

```
conda env create -f conda/notebook_env.yml
conda activate mapmarine2
```

```
## R 3.6
IRkernel::installspec()
devtools::install_github("grelot/geogendivrdata", force = TRUE)
install.packages("rfishbase")
```