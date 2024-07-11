# Multicollinearity, Precision Adjustment, and DAGs for Good and Bad controls

In this lab, we explore key concepts in causal inference: multicollinearity, precision adjustment, and the use of Directed Acyclic Graphs (DAGs) to identify good and bad controls. We start by examining multicollinearity, where highly correlated predictors in a regression model inflate the variances of estimated coefficients. This section includes both theoretical explanations and practical examples to illustrate how multicollinearity can distort regression results and methods to detect and address it.

Next, we discuss precision adjustment, which involves adding variables to regression models to reduce residual variance and increase estimate precision. This section introduces the Lasso method for variable selection, which helps in identifying and including relevant variables while excluding irrelevant ones. We emphasize the importance of selecting appropriate variables to avoid introducing bias. Using DAGs, we demonstrate how to visually represent causal relationships and distinguish between good controls that reduce bias and bad controls that amplify it. Practical exercises and simulations help reinforce these concepts, enabling students to apply them to real-world data.


::::{grid} 1 1 2 3
:class-container: text-center
:gutter: 3

:::{grid-item-card}
:link: lab_2/group3_lab2_python
:link-type: doc

**Python**
^^^

```{image} ../images/python.png
:height: 100
```
:::

:::{grid-item-card}
:link: lab_2/group3_lab2_r
:link-type: doc

**R**
^^^

```{image} ../images/R.png
:height: 100
```
:::

:::{grid-item-card}
:link: lab_2/group3_lab2_julia
:link-type: doc

**Julia**
^^^

```{image} ../images/julia.png
:height: 100
```

:::

::::