---
title: Simple Regression with Python
author: andrea perlato
date: '2019-07-19'
slug: simple-regression-with-python
categories:
  - theory
tags:
  - linear regression
---

<style>
body {
text-align: justify}
</style>

The reticulate package provides a comprehensive set of tools fot interoperability between Python and R.    










```python
# Data Preprocessing Template
# Importing the libraries
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd

# print(r.df.head())

# Importing the dataset
df = pd.read_csv(r"C:\07 - R Website\dataset\PY\Salary_Data.csv") # load the data
df.head(10) # show firt 10 observations
# 
# Preprocessing Input data
```

```
##    YearsExperience   Salary
## 0              1.1  39343.0
## 1              1.3  46205.0
## 2              1.5  37731.0
## 3              2.0  43525.0
## 4              2.2  39891.0
## 5              2.9  56642.0
## 6              3.0  60150.0
## 7              3.2  54445.0
## 8              3.2  64445.0
## 9              3.7  57189.0
```

```python
X = df.iloc[:, 0]
Y = df.iloc[:, 1]
# plt.scatter(X, Y)
# plt.show()
```



<img src="/TheoryPost/2019-07-19-simple-regression-with-python_files/figure-html/unnamed-chunk-3-1.png" width="100%" style="display: block; margin: auto;" />

 
 
 
 























   




