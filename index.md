--- 
title: "Introduction to statistical data analysis in R"
author: "Mario Recker"
site: bookdown::bookdown_site
output:
    bookdown::gitbook:
        config:
            sharing: null
        css: 'style.css'
        includes:
            in_header: _toggle.html
        keep_md: TRUE
linkcolor: blue
documentclass: book
link-citations: yes
description: "Intro to Stats with R"
---

# About {-}




This workshop is intended to introduce the R/RStudio statistical programming environment and how to use it for efficient data handling, data visualisation and data analysis. It is aimed at individuals with little experience in R/Rstudio and basic statistics. For those who are interested in a general intro to R or a refresher, please have a look at the following site for a great introduction to R/RStudio [Introduction to R](https://exeter-data-analytics.github.io/IntroToR/index.html). Equally, much of the material on statistical data analysis are based on the [Statistical Modelling in R](https://exeter-data-analytics.github.io/StatModelling/) workshop. These workshops had been developed by [TJ McKinley](https://medicine.exeter.ac.uk/people/profile/index.php?web_id=TJ_McKinley) from the University of Exeter and JJ Valletta ($\dagger$).


## Workshop structure {-}

This workshop will loosely be structured into the following themes

1. General introduction to R/RStudio
    - variables and data frames
    - functions and loops
    - basic plotting

2. Data handling and visualisation
    - importing data
    - plotting data with `ggplot`
    - data wrangling

3. Statistical analysis 
    - linear models
    - mixed effect models
    - generalised linear models
    - survivial analysis
    - latent class analysis


$~$

The workshop will consist of a mixture between (theoretical) background and hands-on practicals. Specific tasks, designed for you to test your new skills and understanding, are highlighted as

<div class="panel panel-default"><div class="panel-heading"> Task </div><div class="panel-body"> 
This task will be explained here </div></div>

The solution can be revealed by clicking 

<button id="displayTextunnamed-chunk-3" onclick="javascript:toggle('unnamed-chunk-3');">Show: Solution</button>

<div id="toggleTextunnamed-chunk-3" style="display: none"><div class="panel panel-default"><div class="panel-heading panel-heading1"> Solution </div><div class="panel-body">
A solution will appear here.</div></div></div>

However, please make sure you try before clicking on the `Solution` - this is the only way to make sure how fully understood the new concepts.


<!--chapter:end:index.Rmd-->


# General introduction to R/RStudio

Placeholder


## Setting up an R session
## R packages
## Variables, vectors and data frames in R
### Data frames
## Functions in R
### Useful inbuilt functions
### Custom functions
## Basic plotting in R
### Scatter plot
### Line graph
### Combined graph
### Barplot
### Boxplots

<!--chapter:end:1-Introduction.Rmd-->


# Data wrangling and visualisation

Placeholder


## Introduction
## Loading and saving data
### Save / load data as an R object
### Save / load as a CSV file
### Handling Excel files
### Cheatsheet
## Visualisation using `ggplot`
### Aesthetics
### Geoms
### Labels 
### Faceting
### Statistical transformation
### Scales
### Assigning plots to objects
### Putting it all together

<!--chapter:end:2-Data_wrangling_pt1.Rmd-->



## Data wrangling
### Tidy data
### Filter rows
### Sort rows
### Select columns
### Grouping and summarising
### Reshaping datasets
### Mutate
### Dealing with missing data
#### **Detecting missing data** {-}
#### **Removing NA's** {-}

<!--chapter:end:2-Data_wrangling_pt2.Rmd-->


# Introduction to statistical modelling in R

Placeholder


## What is a statistical model? {-}
## Descriptive vs. inferential statistics {-}
## Univariate analysis
### **Mean vs. median** {-}
### **Standard deviation** {-}
### **Interquartile range** {-}
### **Skewness** {-}
### **Kurtosis** {-}
## Multivariate analysis
### **Contingency tables** {-}
#### **Pearson's chi-squared test** {-}
#### **Fisher's exact test** {-}
### **Pearson correlation** {-}
### **Spearman's rank correlation** {-}
### **Correlation vs. causation** {-}

<!--chapter:end:3-Descriptive_statistics.Rmd-->


# Linear Models (LM)

Placeholder


## Simple linear regression
## Linear regression in R
### **Using the `summary()` function**
## Model checking
### **Residuals vs Fitted** {-}
### **Normal Q-Q** {-}
### **Scale-Location** {-}
### **Residuals vs Leverage** {-}
## Prediction
### **Confidence vs prediction interval** {-}
## Multiple linear regression
## Categorical explanatory variables
## Interactions

<!--chapter:end:4-Linear_models.Rmd-->


# Mixed Effect Models (MEM)

Placeholder


#### **Fixed effects** {-}
#### **Random effects** {-}
## Model checking
## Further reading 

<!--chapter:end:5-Mixed_effect_models.Rmd-->


# Generalised Linear Models (GLM)

Placeholder


## Link functions
## Poisson regression (for count data)
### Background
### Poisson regression in R
## Logistic regression (for binary data)
### Background
### Logistic regression in R
### Odds ratios {-}

<!--chapter:end:6-Generalised_linear_models.Rmd-->


# Survival Analysis 

Placeholder


## Terminology and notation 
### Censoring
### Survival and hazard functions
#### **Survival function** {-}
#### **Hazard function** {-}
### Calculating survival times in R
### R libraries and example data
## Kaplan-Meier
### **Median survival time**
## Cox regression model

<!--chapter:end:7-Survival_analysis.Rmd-->

