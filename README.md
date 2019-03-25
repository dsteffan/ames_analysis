# Ames Housing Data

---

### Introduction

There are many features that go in to buying a house. Too many, in fact. First time home buyers risk getting overwhelmed by everything they must consider if they wish to purchase a house.

### Problem Statement:

> How can we narrow down the amount of features into a human-readable, non-technical summary while still retaining accuracy?

To answer this problem, we will use linear regression to analyze our data. Linear regression is a statistical modeling tool that helps us to understand and even quantify the underlying relationships between features. For example, how is the sale price of a house affected by the total square footage of the house? The advantages of linear regression are that the coefficients are easily interpretable. The disadvantage is that it can be hard to tell which features are the most important. We will use Lasso regression to narrow down the number of coefficients and then feed those features back into a linear regression model to interpret those features. 

Throughout the project, a number of submissions were prepared for the kaggle competitions. Although the majority of the time spent on this project was spent cleaning and iterating models with the intention of submitting them to kaggle, these models have been scaled and transformed, and while they are more accurate, they are much harder to interpret for a non-technical audience. For this reason, they were not selected to be presented. 

While the model chosen does do a good job of approximating the price of a house in Ames, Iowa, the model does not generalize well to other regions of the country. A square foot in rural Iowa is going to cost a lot less than a square foot in downtown Seattle, for example. Another drawback of the final model is that it was simple. Simplicity was a goal from the outset, but an experienced homeowner or someone that wanted a more granular look at house prices would not get much use out of this model unless we went through lasso regression again and pruned out less features. 