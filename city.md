---
title: "Estimation of City and Health Region Level COVID-19 Reproduction Number, R0"
output:
  html_document:
    keep_md: true
    highlight: haddock
    number_sections: false
    self_contained: yes
    toc: yes
    toc_depth: 3
    toc_float: no
---

**Date Created:** Jun 01, 2020

**Date Updated:** Jun 14, 2020



<br>


# 1. Overall summary

* **We observed a highly probable infection spread and rate increase in Toronto region and a probable infection rate decrease in Peel region.**
* **We observed a highly probable declining of infection in Montreal.**
* **It's unclear (neither increasing nor decreasing) for other health regions including Durham and York.**
* **No forecast of R0 for areas with low number of daily new cases. Prediction is not completed if the last daily new case number is under 40.**

**For estimation methods please see <https://epiforecasts.io/covid/methods.html>.** 

**Complete model output generated from [the EpiNow R package](https://github.com/epiforecasts/EpiNow) is available at <https://github.com/Kuan-Liu/Kuan-Liu.github.io/tree/master/docs/city-summary>. You can find here, 1) all figures in png format, 2) estimated daily new cases with 50% and 90% credible intervals in case.csv file, 3) estimated and forecast temporal R0 with 50% and 90% Credible intervals in rt.csv file.**

<br>

# 2. Figures and tables

## (1) Estimated temporal R0 and daily new cases for Montreal, Toronto, Durham, Peel and York health regions


Table: Estimated temporal R0 and daily new cases for Montreal, Toronto, Durham, Peel and York health regions as of  Jun 14, 2020

    City       New confirmed cases by infection date    Expected change in daily cases    Effective reproduction no. 
------------  ---------------------------------------  --------------------------------  ----------------------------
   Durham                  15 (5 -- 24)                             Unsure                      1 (0.6 -- 1.4)       
   Laval                   18 (5 -- 27)                             Unsure                     0.9 (0.5 -- 1.2)      
 Monteregie                47 (29 -- 60)                      Likely decreasing                0.9 (0.7 -- 1.1)      
  Montreal                 76 (56 -- 92)                      Likely decreasing                 0.8 (0.7 -- 1)       
    Peel                   43 (30 -- 56)                      Likely decreasing                 0.8 (0.7 -- 1)       
  Toronto                134 (112 -- 158)                     Likely decreasing                 0.9 (0.8 -- 1)       
    York                   28 (15 -- 40)                            Unsure                      1 (0.8 -- 1.4)       

<br>

## (2) Estimated temporal R0 for Montreal, Toronto, Durham, Peel and York health regions

![](docs/city-summary/high_cases_rt_plot.png)

<br>

## (3) Estimated temporal trend on daily new cases for Montreal, Toronto, Durham, Peel and York health regions

![](docs/city-summary/high_cases_plot.png)

<br>

## (4) Estimated current/latest number of daily new cases and R0 for Montreal, Toronto, Durham, Peel and York health regions

![](docs/city-summary/summary_plot.png)
