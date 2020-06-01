---
title: "Estimation of City Level COVID-19 Reproduction Number, R0"
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

**Date Updated:** Jun 01, 2020



<br>


# 1. Overall summary

* **We observed a highly probable declining of infection in Montreal.**
* **It's unclear given the most recent data that Toronto is on the path of declining infection (or on the path of inclining infection)**


**For estimation methods please see <https://epiforecasts.io/covid/methods.html>.** 

**Complete model output generated from [the EpiNow R package](https://github.com/epiforecasts/EpiNow) is available at <https://github.com/Kuan-Liu/Kuan-Liu.github.io/tree/master/docs/city-summary>. You can find here, 1) all figures in png format, 2) estimated daily new cases with 50% and 90% credible intervals in case.csv file, 3) estimated and forecast temporal R0 with 50% and 90% Credible intervals in rt.csv file.**

<br>

# 2. Figures and tables

## (1) Estimated temporal R0 and daily new cases for Montreal and Toronto


Table: Estimated temporal R0 and daily new cases for Montreal and Toronto as of  Jun 01, 2020

   City      New confirmed cases by infection date    Expected change in daily cases    Effective reproduction no. 
----------  ---------------------------------------  --------------------------------  ----------------------------
 Montreal              236 (202 -- 269)                     Likely decreasing                 0.9 (0.8 -- 1)       
 Toronto               178 (152 -- 206)                           Unsure                      1 (0.9 -- 1.1)       

<br>

## (2) Estimated temporal R0 for Montreal and Toronto

![](docs/city-summary/high_cases_rt_plot.png)

<br>

## (3) Estimated temporal trend on daily new cases for Montreal and Toronto

![](docs/city-summary/high_cases_plot.png)

<br>

## (4) Estimated current/latest number of daily new cases and R0 for Montreal and Toronto

![](docs/city-summary/summary_plot.png)
