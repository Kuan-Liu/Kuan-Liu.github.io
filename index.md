---
title: "My COVID-19 Research HUB"

output:
  html_document:
    keep_md: true
    highlight: haddock
    number_sections: false
    self_contained: yes
    toc: yes
    toc_depth: 3
    toc_float: no
    includes: 
      # in_header: google-analytics.html
      # after_body: footer.html
---

**Date Created:** June 01, 2020

**Date Updated:** Jun 01, 2020



<br>

# From the author

**Thank you for your interest in my COVID-19 data visualization and data analysis work! I created this website to provide a one-stop shop for readers to view all my current and future COVID related projects.**

**I don't intent to style or format this webpage (please excuse the plainness). Feel free to reach me at kuan.liu@mail.utoronto.ca. You can also find me on [Twitter](https://twitter.com/KuanLiu2). For those of you who are interested to learn more about me, I direct you to visit my other website <https://www.kuan-liu.com/>.**

<br>

# Current Projects

## 1. COVID-19 Testing Trend in Canada [(link)](https://rpubs.com/kuanstat/testing_can)

This is a joint work with [Alexandra Bushby](https://www.linkedin.com/in/alexandra-bushby-571b65168/) and [Thai-son Tang](https://www.linkedin.com/in/thaison-tang/). Our project website is hosted at <https://rpubs.com/kuanstat/testing_can>. We provide descriptive data visualization on COVID-19 testing data in Canada. I started this project back in late March. 

We are planning to move the website content to a new shiny app in June using primarily the official federal and provincial testing data. The current analysis uses primary the testing data provided by [the COVID-19 Canada Open Data Working Group](https://github.com/ishaberry/Covid19Canada). 

Highlight of the project visualization content: 

* Total number of tests conducted
* Total number of tests conducted per 100,000 population
* Comparison of total tests per 100,000 population to the total number of cases per 100,000
* Total number of daily new tests conducted
*Proportion of patients tested positive out of the number of tests conducted



## 2. COVID-19 Canada Dashboard [(link)](https://kuan-liu.shinyapps.io/canada_dash/)

This is a joint work with [Rose Garrett](https://twitter.com/rose_carrot). Our interactive dashboard is hosted at <https://kuan-liu.shinyapps.io/canada_dash/>. We provide descriptive data visualization on Canada COVID-19 confirmed, active, recovered cases, and deaths data provided by [the COVID-19 Canada Open Data Working Group](https://github.com/ishaberry/Covid19Canada). I coded the original version using Rami Krispin's Covid19 Italy [dashboard](https://github.com/RamiKrispin/italy_dash) as template back in early April.

Highlight of the dashboard content: 

* A summary page on nationwide data
    + Overall distribution of cases, daily new Confirmed, fatal and recovered cases
    + Daily percentage increase on confirmed and fatal cases 
    + Case trajectory with comparison to other countries
    + Confirmed and fatal cases distribution by province and territory 
* A case map page (using Leaflet)
* A summary page for Toronto, Ontario and Quebect
* A page with Canada COVID-19 data table

Sample plotly figures from our dashboard

* 1. Confirmed cases by province and territory
* 2. Daily new Confirmed, fatal and recovered cases

![Confirmed cases by province and territory](docs/figures/casebyprov_can.png)
![Daily new Confirmed, fatal and recovered cases](docs/figures/dailynew_can.png)

<br>

## 3. Estimation of Regional Temporal Reproduction Number R0 of COVID-19

This is work is produced by replicating the subnational analysis provided at <https://epiforecasts.io/covid/> by a team of researcher lead by [Prof. Sebastian Funk](https://www.lshtm.ac.uk/aboutus/people/funk.sebastian) the at Centre for the Mathematical Modelling of Infectious Disases, London School of Hygiene and Tropical Medicine.

Two R packages developed by the same team were used, [the EpiNow R package](https://github.com/epiforecasts/EpiNow) and [the EpiSoon R package](https://github.com/epiforecasts/EpiSoon). In addition, the forecastHybrid R package developed by [David Shaub and Peter Ellis](https://github.com/ellisp/forecastHybrid) is used to produce a 14-day forecast on R0. Canada data is extracted again from the open-access data provided by [the COVID-19 Canada Open Data Working Group](https://github.com/ishaberry/Covid19Canada). 

Estimation results are shared on this website on subtabs.

<br>

# Future Projects

I submitted a team project proposal to the University of Toronto COVID-19 Student Engagement Award mid May. Our project is titled, "Using Data Visualization and Crowdsourcing Survey to study COVID-19 Testing Capacity, Protocol, and Barriers in Canada". If funded, in addition to creating a testing data dashboard, we will conduct a crowdsourcing survey study to understand public preception on COVID-19 testing. In particular, we are interested to learn concerns people might have when requesting for a test, completing a test and waiting for test results. Stay tuned!







