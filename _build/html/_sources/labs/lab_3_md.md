# Neyman Orthogonality, Orthogonal Learning, and Double Lasso

In this lab, we begin by demonstrating the Neyman Orthogonality Condition, which is fundamental for ensuring the robustness of certain estimators in high-dimensional data settings. This proof helps students understand the theoretical underpinnings that make orthogonal estimators effective in eliminating bias.

We then move on to practical applications by replicating an experiment on orthogonal learning. Through simulations with different trial sizes (B = 100, B = 1000, B = 10000), we observe the distributions of histograms and analyze where the orthogonal and naive estimators are centered. This includes an econometric explanation of why these distributions occur as they do. The lab emphasizes the implementation of parallel computing in Python, R, and Julia to demonstrate how it significantly reduces running times.

Finally, we analyze school data to implement and compare various approaches: OLS, Double Lasso with cross-validation, Double Lasso with theoretical lambda, and Double Lasso using the "partialling out" method. By plotting the main coefficients and their confidence intervals, we explore the effectiveness of these methods and discuss the observed patterns. This comprehensive analysis allows students to apply advanced econometric techniques to real-world data, enhancing their skills in causal inference and machine learning.


::::{grid} 1 1 2 3
:class-container: text-center
:gutter: 3

:::{grid-item-card}
:link: lab_3/group3_lab3_python
:link-type: doc

**Python**
^^^

```{image} ../images/python.png
:height: 100
```
:::

:::{grid-item-card}
:link: lab_3/group3_lab3_r
:link-type: doc

**R**
^^^

```{image} ../images/R.png
:height: 100
```
:::

:::{grid-item-card}
:link: lab_3/group3_lab3_julia
:link-type: doc

**Julia**
^^^

```{image} ../images/julia.png
:height: 100
```

:::

::::