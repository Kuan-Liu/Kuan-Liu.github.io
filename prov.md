---
title: "Estimation of Provincial Level COVID-19 Reproduction Number, R0"
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

**Date Updated:** Jun 25, 2020



<br>

# 1. Overview on Estimation Methods

For estimation methods please see <https://epiforecasts.io/covid/methods.html>. 

In a nutshell, the reproduction number is estimated with a stochastic (infection) generation model under a Bayesian framework using MCMC with an informative gamma prior (mean 2.6 and standard deviation 2, based on initial Wuhan R0 estimates).

Estimation of R0 accounts for reporting delay, that is defined as the time between sympton onset and reporting. The delay time distribution is estimated using an international data (avaliable at <https://github.com/epiforecasts/NCoVUtils>) while sympton onset date and reporting date are both recorded. Unfortunately, there is no open-access data on such information in Canada, so there could be potential bias using an estimate of this delay from data of other Countries.

Last but not least, a 14-day forecast of R0 is conducted with the ensumble time series models using [the forecastHybrid R package](https://github.com/ellisp/forecastHybrid) developed by David Shaub and Peter Ellis.

**Complete model output generated from [the EpiNow R package](https://github.com/epiforecasts/EpiNow) is available at <https://github.com/Kuan-Liu/Kuan-Liu.github.io/tree/master/docs/regional-summary>. You can find here, 1) all figures in png format, 2) estimated daily new cases with 50% and 90% credible intervals in case.csv file, 3) estimated and forecast temporal R0 with 50% and 90% Credible intervals in rt.csv file.**

<br>

# 2. Provincial Level Estimation Results

## (1) Overall summary

* **We observed a probable infection spread and rate decrease in Quebec.**
<!-- * **We observed a highly probable declining of infection in Quebec.** -->
* **It's unclear (neither increasing nor decreasing) for Alberta, British Columbia and Ontario.**
* **No forecast of R0 for BC due to low number of daily new cases. Prediction is not completed if the last daily new case number is under 40.**

The estimation uncertainly is quite substantial (translate directly to wide credible interval) for British Columbia R0 estimand. Thus, the conclusion of probable infection in BC is sensitive to new data on daily new confirmed cases. Our model conclusion will likely change for BC with new data.

<br>

## (2) Figures and tables

### (i) Estimated temporal R0 and daily new cases for Alberta, BC, Ontario and Quebec


Table: Estimated temporal R0 and daily new cases for Alberta, BC, Ontario and Quebec as of  Jun 25, 2020

 Province    New confirmed cases by infection date    Expected change in daily cases    Effective reproduction no. 
----------  ---------------------------------------  --------------------------------  ----------------------------
 Alberta                 44 (28 -- 56)                            Unsure                      1 (0.8 -- 1.3)       
    BC                   17 (6 -- 25)                             Unsure                     1.2 (0.8 -- 1.6)      
 Ontario               227 (191 -- 259)                           Unsure                     1.1 (0.9 -- 1.2)      
  Quebec                92 (71 -- 111)                      Likely decreasing                 0.9 (0.7 -- 1)       

<br>

### (ii) Estimated temporal R0 for Alberta, BC, Ontario and Quebec

![](docs/regional-summary/high_cases_rt_plot.png)

<br>

### (iii) Estimated temporal trend on daily new cases for Alberta, BC, Ontario and Quebec

![](docs/regional-summary/high_cases_plot.png)

<br>

### (iv) Estimated current/latest number of daily new cases and R0 for Alberta, BC, Ontario and Quebec

![](docs/regional-summary/summary_plot.png)
