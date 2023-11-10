Proposal
================
Junjie Hu
2023-11-09

## The group members (names and UNIs)

Junjie Hu jh4617

Ruixi Li rl33298

Xuan Lu xl3214

Tianyun Jiang tj2519

Qinting Shen qs2261

## The tentative project title

HIV/AIDS Surveillance Data Analysis across Countries

## The motivation for this project

The primary goal of this project is to analyze information on HIV
prevalence, incidence rates, and AIDS mortality from available studies.
This project also helps identify the most vulnerable gender,
sub-population, and geographic region.

## The intended final products

Multiple dashboards/web pages reflect the prevalence and incidence rates
of HIV across countries and subgroups.

## The anticipated data sources

United States Census’s HIV/AIDS Surveillance Data Base

``` r
library(tidyverse)
```

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.1.3     ✔ readr     2.1.4
    ## ✔ forcats   1.0.0     ✔ stringr   1.5.0
    ## ✔ ggplot2   3.4.3     ✔ tibble    3.2.1
    ## ✔ lubridate 1.9.2     ✔ tidyr     1.3.0
    ## ✔ purrr     1.0.2     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

``` r
hiv_df = 
  read.csv("hiv_joined_data.csv") |>
  janitor::clean_names() 
```

## Planned analyses

- Exploratory analysis

- Hypothetical test

- ANOVA

- T-test

- Regression

## Visualizations

- A map reports the HIV prevalence and incidence rates in each country
  (plotly)

- A chart reports the HIV prevalence and incidence rates of each
  subpopulation over time (plotly)

- A chart shows the difference of HIV prevalence and incidence rates
  across gender (ggplot)

- A chart shows the HIV prevalence and incidence rates in Capital city
  versus Rural area (ggplot)

- A chart shows the HIV prevalence and incidence rates across continents
  (ggplot)

- A table indicating the countries/regions with the highest HIV
  prevalences and incidence rate

## Coding challenges

- Map formulation

- Data quality control, including data cleaning and data management

## The planned timeline

- Nov. 9 - Nov. 11: look for other potential dataset and write proposal

- Nov.11 - Nov.13: Familiarize the dataset(s) and clean the dataset

- Nov.14 - Nov.21: Coding and plotting

- Nov. 22 - Nov. 29: Writing the report

- Nov. 30 - Dec. 8: Shooting video, building website, and project
  finalization
