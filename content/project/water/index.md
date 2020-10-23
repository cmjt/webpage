---
title: Develop an R-shiny tool to allow to calculate site-adjusted water quality guidelines
summary: data wrangling, programming, visualisation
tags:
- honours
- masters
---

Co-supervised by [Dr Jennifer Gadd](https://niwa.co.nz/people/jennifer-gadd), head of the Urban Aquatic Environments group at [NIWA](https://niwa.co.nz/).

The water quality guidelines for zinc in freshwater are based on a species sensitivity distribution (SSD), which has a probabilistic model, such as log-normal, log-logistic or Burr Type III, fitted to calculate guidelines (at varying percentile levels). The method for zinc first requires the individual data values for the SSD to be adjusted to a standard water quality, either default values, or to user-added values. These are three multiple linear regression models used for this (one each for fish, invertebrates and algae) to account for the fact that zinc is less toxic in the presence of dissolved organic carbon (DOC), calcium and magnesium (hardness) and at low pH. An R shiny tool is required that would allow people to calculate the guideline at whatever pH, hardness and DOC they want, based on what they measure in their water.  The data need to be adjusted based on each MLR model, then the SSD generated, and guidelines calculated.

The student should have good `R` programming skills but is not expected have come across  [RShiny](https://shiny.rstudio.com/); a creative streak would be an advantage.