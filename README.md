# R-stable

[![DOI](https://zenodo.org/badge/49820667.svg)](https://zenodo.org/badge/latestdoi/49820667)
[![license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://raw.githubusercontent.com/inbo/RStable/master/LICENSE)
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![](https://images.microbadger.com/badges/image/inbobmk/rstable.svg)](https://microbadger.com/images/inbobmk/rstable)
[![](https://img.shields.io/docker/pulls/inbobmk/rstable.svg)](https://hub.docker.com/r/inbobmk/rstable)
[![](https://img.shields.io/docker/automated/inbobmk/rstable.svg)](https://hub.docker.com/r/inbobmk/rstable/builds)

A stable Docker image with R. The version of most software is hard-coded. Each tag points to a specific R version. We have two special tags: `latest` and `oldrel`. `latest` always points to the most recent R version available in RStable. `oldrel` points to the most recent R version in RStable from the previous major release. E.g. when `latest` points to `R 3.4.1`, `oldrel` will point to `R 3.3.3`.

| Available software | Version         |
| ------------------ | --------------- |
|             Ubuntu |     18.04.1 LTS | 
|               qpdf |           8.0.2 | 
|             pandoc |         2.2.3.2 | 
|                  R |           3.5.1 | 
|         KernSmooth |         2.23-15 | 
|               MASS |          7.3-50 | 
|             Matrix |          1.2-14 | 
|               boot |          1.3-20 | 
|              class |          7.3-14 | 
|            cluster |         2.0.7-1 | 
|          codetools |          0.2-15 | 
|            foreign |          0.8-70 | 
|            lattice |         0.20-35 | 
|               mgcv |          1.8-24 | 
|               nlme |         3.1-137 | 
|               nnet |          7.3-12 | 
|              rpart |          4.1-13 | 
|            spatial |          7.3-11 | 
|           survival |          2.42-6 | 
|                 BB |       2014.10-1 | 
|                 BH |        1.66.0-1 | 
|                DBI |           1.0.0 | 
|                 DT |             0.4 | 
|               INLA |        18.07.12 | 
|       MatrixModels |           0.4-1 | 
|                NMF |          0.21.0 | 
|                 R6 |           2.2.2 | 
|       RColorBrewer |           1.1-2 | 
|              RCurl |       1.95-4.11 | 
|              RODBC |          1.3-15 | 
|        RPostgreSQL |           0.6-2 | 
|            RSQLite |           2.1.1 | 
|             Rcgmin |       2013-2.21 | 
|               Rcpp |         0.12.18 | 
|          RcppEigen |       0.3.3.4.0 | 
|             Rvmmin |       2018-4.17 | 
|                XML |       3.98-1.16 | 
|         assertthat |           0.2.0 | 
|             aws.s3 |          0.3.12 | 
|      aws.signature |           0.4.4 | 
|          backports |           1.1.2 | 
|          base64enc |           0.1-3 | 
|             bibtex |           0.4.2 | 
|              bindr |           0.1.1 | 
|           bindrcpp |           0.2.2 | 
|                bit |          1.1-14 | 
|              bit64 |           0.9-7 | 
|             bitops |           1.0-6 | 
|               blob |           1.1.1 | 
|           bookdown |             0.7 | 
|               brew |           1.0-6 | 
|            caTools |        1.17.1.1 | 
|              callr |           3.0.0 | 
|                cli |           1.0.0 | 
|         colorspace |           1.3-2 | 
|         commonmark |             1.5 | 
|               covr |           3.1.0 | 
|             crayon |           1.3.4 | 
|          crosstalk |           1.0.0 | 
|               curl |             3.2 | 
|         data.table |          1.11.4 | 
|             dbplyr |           1.2.2 | 
|            debugme |           1.1.0 | 
|               desc |           1.2.0 | 
|           devtools |          1.13.6 | 
|            dfoptim |        2018.2-1 | 
|          dichromat |           2.0-0 | 
|             digest |          0.6.16 | 
|         doParallel |          1.0.11 | 
|              dplyr |           0.7.6 | 
|           evaluate |            0.11 | 
|              fansi |           0.3.0 | 
|            foreach |           1.4.4 | 
|            formatR |             1.5 | 
|          geosphere |           1.5-7 | 
|            ggplot2 |           3.0.0 | 
|              git2r |          0.23.0 | 
|          git2rdata |           0.0.3 | 
|               glue |           1.3.0 | 
|           gridBase |           0.4-7 | 
|             gtable |           0.2.0 | 
|             hexbin |          1.27.2 | 
|              highr |             0.7 | 
|                hms |           0.4.2 | 
|          htmltools |           0.3.6 | 
|        htmlwidgets |             1.2 | 
|             httpuv |           1.4.5 | 
|               httr |           1.3.1 | 
|             igraph |           1.2.2 | 
|              irlba |           2.3.2 | 
|          iterators |          1.0.10 | 
|           jsonlite |             1.5 | 
|              knitr |            1.20 | 
|           labeling |             0.3 | 
|              later |           0.7.4 | 
|           lazyeval |           0.2.1 | 
|              lintr |           1.0.2 | 
|               lme4 |        1.1-18-1 | 
|          lubridate |           1.7.4 | 
|           magrittr |             1.5 | 
|           markdown |             0.8 | 
|            memoise |           1.1.0 | 
|               mime |             0.5 | 
|              minqa |           1.2.4 | 
|          multimput |         0.2.8.1 | 
|            munsell |           0.5.0 | 
|            mvtnorm |           1.0-8 | 
|             nloptr |           1.0.4 | 
|           numDeriv |        2016.8-1 | 
|               odbc |           1.1.6 | 
|            openssl |           1.0.2 | 
|          optextras |        2016-8.8 | 
|             optimx |        2013.8.7 | 
|              osmar |           1.1-7 | 
|             pander |           0.6.2 | 
|             pillar |           1.3.0 | 
|           pkgbuild |           1.0.0 | 
|          pkgconfig |           2.0.2 | 
|            pkgload |           1.0.0 | 
|           pkgmaker |            0.27 | 
|              plogr |           0.2.0 | 
|             plotly |           4.8.0 | 
|               plyr |           1.8.4 | 
|               pool |         0.1.4.1 | 
|             praise |           1.0.0 | 
|        prettyunits |           1.0.2 | 
|           processx |           3.2.0 | 
|            profvis |           0.3.5 | 
|           promises |           1.0.1 | 
|                 ps |           1.1.0 | 
|              purrr |           0.2.5 | 
|           quadprog |           1.5-5 | 
|              readr |           1.1.1 | 
|           registry |             0.5 | 
|           reshape2 |           1.4.3 | 
|                rex |           1.1.2 | 
|              rgdal |           1.3-4 | 
|              rgeos |          0.3-28 | 
|              rlang |           0.2.2 | 
|          rmarkdown |            1.10 | 
|           rngtools |           1.3.1 | 
|           roxygen2 |           6.1.0 | 
|          rprojroot |           1.3-2 | 
|         rstudioapi |             0.7 | 
|             scales |           1.0.0 | 
|             setRNG |        2013.9-1 | 
|              shiny |           1.1.0 | 
|               snow |           0.4-2 | 
|           snowfall |        1.84-6.1 | 
|        sourcetools |           0.1.7 | 
|                 sp |           1.3-1 | 
|         stringdist |         0.9.5.1 | 
|            stringi |           1.2.4 | 
|            stringr |           1.3.1 | 
|             svUnit |          0.7-12 | 
|           testthat |           2.0.0 | 
|             tibble |           1.4.2 | 
|              tidyr |           0.8.1 | 
|         tidyselect |           0.2.4 | 
|            tinytex |             0.8 | 
|             ucminf |           1.1-4 | 
|               utf8 |           1.1.4 | 
|        viridisLite |           0.3.0 | 
|            webshot |           0.5.0 | 
|            whisker |           0.3-2 | 
|              withr |           2.1.2 | 
|               xfun |             0.3 | 
|               xml2 |           1.2.0 | 
|             xtable |           1.8-3 | 
|               yaml |           2.2.0 | 
