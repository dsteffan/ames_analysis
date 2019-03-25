# Ames Housing Data

---

### Introduction

There are many features that go in to buying a house. Too many, in fact. First time home buyers will get overwhelmed by everything they must consider if they wish to purchase a house. 

### Problem Statement:

> Narrow down the amount of features into a working, human-readable, non-technical summary.

To answer this problem, we will use linear regression to analyze our data. Linear regression is a statistical modeling tool that helps us to understand and even quantify the underlying relationships between features. For example, how is the sale price of a house affected by the total square footage of the house? The advantages of linear regression are that the coefficients are easily interpretable. The disadvantage is that it can be hard to tell which features are the most important. We will use Lasso regression to narrow down the number of coefficients and then feed those features back into a linear regression model to interpret those features. 