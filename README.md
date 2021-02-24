# capstoneProject1

## Aim:
The goal of this study is to apply concepts of probability and statistics, data analytics, and visualization that I learned so far to a dataset using Python, Numpy, Pandas, and Matplotlib:

## Dataset
Medical Cost Personal Datasets:

https://www.kaggle.com/mirichoi0218/insurance

This dataset shows a yearly medical cost for individuals in United States.

## Working Hypothesis:
I would like to test hypothesis whether there are difference between the medical insurance cost of (1) men and women, (2) smoker and nonsmoker, and (3) their body mass index (BMI) based on their personal information described in the dataset.

Null Hypothesis: 

H0 = 0

Alternative Hypothesis:

H1 ≠ 0

## Graphs:

![](image/overallgraphs.png)

![](image/overallcorrmatrix.png)

![](image/scatterplot.png)

Gender:

![](image/corrmatrix_gender.png)

![](image/graphs_gender.png)

Smoker:

![](image/graphs_smoker.png)

BMI:

![](image/graphs_bmi.png)

age: ANOVA: statistic = 5.0646, p-value = 0.0005, significantly different

charges: ANOVA: statistic = 14.4182, p-value = 0.0000, significantly different

children: ANOVA: statistic = 0.1797, p-value = 0.9490, not significant

region: ANOVA: statistic = 2.0785, p-value = 0.0814, not significant

region: northeast = 0, southeast = 1, northwest = 2, southwest = 3