# Intro to Partialling-out and Lasso Cross-validation

In this lab, we cover the concepts of partialling-out and Lasso cross-validation within the context of causal inference and machine learning. We begin by introducing the partialling-out method, which helps isolate the effect of a variable of interest by removing the influence of other covariates. This is done through a series of regression steps where we first regress the covariates on the variable of interest, then use the residuals in a subsequent regression to estimate the causal effect. This method allows for a clearer interpretation of the causal relationship by mitigating the bias introduced by confounding variables.

Next, we delve into the Lasso method, a regularization technique used for variable selection and shrinkage in high-dimensional data. The lab demonstrates how to implement Lasso regression and use cross-validation to select the optimal penalty parameter (alpha). We perform cross-validation by splitting the data into training and validation sets, iterating over a range of alpha values, and evaluating the model's performance based on mean squared error (MSE). The lab concludes with training the final model using the best alpha value, assessing its performance on test data, and interpreting the results.


::::{grid} 1 1 2 3
:class-container: text-center
:gutter: 3

:::{grid-item-card}
:link: lab_1/group3_lab1_python
:link-type: doc

**Python**
^^^

```{image} ../images/python.png
:height: 100
```
:::

:::{grid-item-card}
:link: lab_1/group3_lab1_r
:link-type: doc

**R**
^^^

```{image} ../images/R.png
:height: 100
```
:::

:::{grid-item-card}
:link: lab_1/group3_lab1_julia
:link-type: doc

**Julia**
^^^

```{image} ../images/julia.png
:height: 100
```

:::

::::