---
title       : Inequality
subtitle    : Comparing income distributions
author      : Linus Gustafsson
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class #id 

## Introduction

Comparing inequality of different income distributions is associated with a number of problems. For example, different measures of inequality will rank income distributions differently,
and distributions that are very different can often have the same value for some inequality measures. The purpose of this application is to allow the user to compare different income distributions, by:

- Generating two separate income distributions
- Comparing measures of inequality for the two distributions
- Plot the income distributions and Lorenz curves

---

## Usage

Create an income distribution from two different subgroups by selecting the following paramaters for each group:

1. Group size
2. Mean income
3. Standard deviation of income

---

## Output


<img src="assets/fig/plots-1.png" title="plot of chunk plots" alt="plot of chunk plots" style="display: block; margin: auto;" />

<!-- html table generated in R 3.2.0 by xtable 1.7-4 package -->
<!-- Sun May 24 18:50:24 2015 -->
<table border=1>
<tr> <th> Gini coefficient </th> <th> Ratio P90 to P10 </th> <th> Coefficient of variation </th>  </tr>
  <tr> <td align="right"> 0.32 </td> <td align="right"> 4.70 </td> <td align="right"> 0.59 </td> </tr>
   </table>

---

## Future extensions

- Allow the user to choose which distributions to draw random samples from
- Add more control of distributions
- Add additional measures of income inequality
- Add possibility to make comparison with actual data by selected countries
