---
title       : Introduce To My App
subtitle    :  
author      : tokey
job         : Data Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      #
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
ext_widgets: {rCharts: [libraries/nvd3]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Side bar Panel

The APP is used to predict the weight of children from their age and height. 

In the side bar Panel,there are 3 parts you can select or input value:  

1. First part: Select the gender of the children you decide to analyse;  

2. Second part:  Input the age and height which you want to use to predict the chlid's weight;  

3. Third part:   Give the number of observations to view;

--- .class #id

## The result of the Summary

The Summary gives the details of the data under the gender you selected.  

It gives the following Basic statistics:
- Min  
- 1st Qu  
- Median  
- Mean  
- 3rd Qu  
- Max  

--- .class #id 

## The result of the Regression

The regression part give the relationship between the weight and age,height under different gender.  

For example,when you chose gender 'M',the result of regression model are:

```
## (Intercept)         age      height 
##   1.9181597   0.4505176   0.4069768
```

--- .class #id 


## The result of the Prodict and Observations

__predict__  
    Give the age and height ,the predict will give the predicted weight;

__Observations__    
  The the number of Observations to show is depending on the value you input in "Number of observations to view".

