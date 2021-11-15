# **Health Innovation Lab** <img src="man/figures/new_hil_icon.png" align="right" width="26%">


<!-- badges: start -->

[![R-CMD-check](https://github.com/healthinnovation/lis/workflows/R-CMD-check/badge.svg)](https://github.com/healthinnovation/lis/actions)
[![Lifecycle:experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

<!-- badges: end -->

## 🔵 **Who we are**

We are a multidisciplinary team focused on **designing and evaluating innovative and accessible technologies to improve people's health**. We promote the **use of technologies and open data** in order to lower implementation barriers, reproducibility and increase the impact of innovation proposals. 

Our main lines of research include the development of diagnostic and detection systems, development of tools for environmental parameter detection, data science and big data applied to tropical diseases, and geospatial analysis of mobility and migration patterns.

## 🔵 **Package installation**

You can install the trial version from
[GitHub](https://github.com/):
                             
The following code just copy and paste into the R console:

```
if(!require("remotes")) install.packages("remotes")
remotes::install_github("healthinnovation/innovar")
```
```
library(innovar)
data("Peru")
head(Peru)
```
```
Simple feature collection with 6 features and 8 fields
geometry type:  MULTIPOLYGON
dimension:      XY
bbox:           xmin: -78.03582 ymin: -6.986709 xmax: -77.61757 ymax: -5.94494
geographic CRS: WGS 84
# A tibble: 6 × 9
  ubigeo                       geometry reg.code reg   prov.code prov 
  <chr>              <MULTIPOLYGON [°]> <chr>    <chr> <chr>     <chr>
1 010101 (((-77.84657 -6.205922, -77.8… 01       AMAZ… 01        CHAC…
2 010102 (((-77.71853 -6.01407, -77.72… 01       AMAZ… 01        CHAC…
3 010103 (((-77.8963 -6.730613, -77.89… 01       AMAZ… 01        CHAC…
4 010104 (((-77.61908 -6.274398, -77.6… 01       AMAZ… 01        CHAC…
5 010105 (((-77.7232 -6.038754, -77.72… 01       AMAZ… 01        CHAC…
6 010106 (((-77.78106 -6.926629, -77.7… 01       AMAZ… 01        CHAC…
# … with 3 more variables: distr.code <chr>, distr <chr>,
#   capital <chr>
```

# 🔵 **Our social networks** 
<p align="left">
 <a href = "https://www.facebook.com/imt.innovlab">
 <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a> <a href="https://twitter.com/imt_innovalab"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"></a> <a href="https://www.instagram.com/imtavh_innovalab/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a> <a href="https://www.innovalab.info/"><img src="https://img.shields.io/badge/Innovalab_web-000?style=for-the-badge&logo=wix&logoColor=white"></a> <a href="https://linktr.ee/innov_lab"><img src="https://img.shields.io/badge/linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=whit"></a>
</p>

