# Dissertation

These scripts combine a Bayesian network with an ensemble of deep feedforward neural networks, for the purpose of estimating process criticality accident risk.

I generated the MCNP input decks using **generate.R** and **build.R** and ran them on large clusters at Lawrence Livermore National Laboratory using different scripts, which I haven't uploaded to GitHub.

**dist.R** needs to be run for the distribution fit called in **source.Rmd** (e.g., "gamma"). Once that's done, everything can be run from **source.Rmd**.

I run these scripts on an AMD Ryzen 7 1700 3.0 GHz 8-core CPU and an Nvidia GeForce GTX 1080 8 GB GDDR5X graphics card. For a more complete description of my build, please e-mail me.

## Prerequisites
MCNP6.2  
ENDF/B-VII.1 Nuclear Data

## R Packages
bnlearn  
caret  
EnvStats  
fitdistrplus  
ggplot2  
igraph  
keras  
magrittr  
parallel  
scales  
