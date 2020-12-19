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

**Date Updated:** Dec 19, 2020



<br>


# 1. Overall summary

* **We observed probable infection rate increase in Toronto, Peel, Monteregie, and Montreal health regions.**
<!-- * **We observed probable increase of infection in Peel, Toronto, Monteregie, and Montreal.with estimated daily new cases at 596 (535 – 652) in Peel and 469 (411 – 512) in Toronto** -->
<!-- * **It's unclear (neither increasing nor decreasing) for Toronto and Montreal.** -->
<!-- * **No forecast of R0 for areas with low number of daily new cases. Prediction is not completed if the last daily new case number is under 40.** -->

**For estimation methods please see <https://epiforecasts.io/covid/methods.html>.** 

**Complete model output generated from [the EpiNow R package](https://github.com/epiforecasts/EpiNow) is available at <https://github.com/Kuan-Liu/Kuan-Liu.github.io/tree/master/docs/city-summary>. You can find here, 1) all figures in png format, 2) estimated daily new cases with 50% and 90% credible intervals in case.csv file, 3) estimated and forecast temporal R0 with 50% and 90% Credible intervals in rt.csv file.**

<br>

# 2. Figures and tables

## (1) Estimated temporal R0 and daily new cases for Monteregie, Montreal, Toronto and Peel health regions


Table: Estimated temporal R0 and daily new cases for Monteregie, Montreal, Toronto and Peel health regions as of  Dec 19, 2020

|    City    | New confirmed cases by infection date | Expected change in daily cases | Effective reproduction no. |
|:----------:|:-------------------------------------:|:------------------------------:|:--------------------------:|
| Monteregie |           260 (223 -- 297)            |       Likely increasing        |       1.1 (1 -- 1.2)       |
|  Montreal  |           663 (595 -- 723)            |           Increasing           |       1.1 (1 -- 1.2)       |
|    Peel    |           498 (442 -- 551)            |       Likely increasing        |       1.1 (1 -- 1.1)       |
|  Toronto   |           744 (669 -- 825)            |           Increasing           |      1.2 (1.1 -- 1.2)      |

<br>

## (2) Estimated temporal R0 for Monteregie, Montreal, Toronto and Peel health regions

![](docs/city-summary/high_cases_rt_plot.png)

<br>

## (3) Estimated temporal trend on daily new cases for Monteregie, Montreal, Toronto and Peel health regions

![](docs/city-summary/high_cases_plot.png)

<br>

## (4) Estimated current/latest number of daily new cases and R0 for Monteregie, Montreal, Toronto and Peel health regions

![](docs/city-summary/summary_plot.png)
