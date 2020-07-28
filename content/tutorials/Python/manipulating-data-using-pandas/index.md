---
title: Manipulating data using Pandas
linktitle: Manipulating data using Pandas
toc: true
type: docs
date: "2020-07-25"
draft: false
authors:
- Christopher Hoover
menu:
  GettingStarted:
    parent: Python
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

## Introduction
Pandas is a Python library that extends NumPy to make data exploration and manipulation easier. This page is a quick reference for using Pandas for data manipulation.

## Vector operations

Perform operations on a series.

```{python}
#adds 10 to every instance in the data series
data = data + 10
```
Useful, for example, if you want to find the difference between last year and this year data.
```{python}
#Create a new series by subtracting one series from another
new_column = df['column1'] - df['column2']  
```



```
