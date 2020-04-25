# mass_shooting_intervals

Abstract
------
Lin et al. ([2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6193640/)) found that the time interval between mass shootings has been drastic decreasing in the past three decades, suggesting that the rate of shootings are increasing. I was able to replicate all of the results from Lin et al. ([2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6193640/)), but while I was able to replicate the inconclusive results in table 1, I was not able to replicate the exact zero-inflated poisson model. My extension broke down the interval trends between different venues of shootings showing in figure 2 of Lin et al. ([2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6193640/)). I found that the interval trend of mass school shootings remained relatively steady while the interval between mass workplace shootings and other mass shootings drastically decreased since 2008. This suggests that more research should be done looking at why workplace mass shootings has specifically increased drastically since 2015.

Repo Guide
------
+ /raw-data : the raw data publicly available used by Lin et al.
+ What have we learned from the time trend of mass shootings in the U.S..pdf : PDF copy of the paper
+ bib.bib : bibliography of all the sources I used
+ mass_shooting_interval.Rmd : Rmd with all my code for the replication
+ mass_shooting_interval.Pdf : Pdf of my replication paper
