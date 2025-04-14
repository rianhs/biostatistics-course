# Scales of measurement

**Scales of measurement** is the classification of [variables](variable.md) according to how they are measured and the type of information they provide for analysis. It describes how variables are quantified, categorized, and interpreted. Each scale determines not only the kind of [data](data.md) collected but also the mathematical operations and statistical techniques that can be appropriately applied. Understanding these scales is essential for selecting valid methods of analysis and drawing meaningful conclusions.

## Types

Variables are commonly classified into four levels of measurement: nominal, ordinal, interval, and ratio. These scales reflect increasing levels of mathematical structure and determine which types of comparisons and transformations are meaningful.

The nominal scale classifies variables into distinct, non-overlapping categories that have no intrinsic order. These values serve solely as labels and cannot be ranked or subjected to arithmetic operations. Nominal data can be counted, summarized by frequency or proportion, and analyzed using non-parametric methods, such as the chi-square test. Examples include species (e.g., dog, cat, horse), sex (male, female), or blood type. You can determine how many individuals belong to each category, but you cannot rank or average nominal values.

The ordinal scale organizes variables into categories that have a meaningful order, though the intervals between values are not necessarily equal or consistent. These variables can be ranked and summarized using medians or percentiles, but arithmetic operations such as addition or subtraction are not valid. Ordinal data are often analyzed using non-parametric tests, such as the Mann–Whitney U test or the Kruskal–Wallis test. Examples include body condition scores (e.g., poor, fair, good), pain severity levels (mild, moderate, severe), or disease stages (Stage I, II, III). Although the categories have a clear order, the exact differences between them are not quantifiable.

The interval scale consists of numerical values with equal intervals between them, but it lacks a true zero point. This allows for subtraction and averaging, but not for meaningful ratios or multiplication. For instance, while the difference between 20 °C and 10 °C is 10 degrees, it would be incorrect to say that 20 °C is "twice as hot" as 10 °C. Interval data can be analyzed using parametric methods, such as t-tests, ANOVA, or correlation, when assumptions are met. Examples include temperature in Celsius or Fahrenheit, calendar years, and pH levels. Differences between values are meaningful, but the absence of a true zero limits the interpretability of proportions.

The ratio scale includes all the properties of the interval scale, with the added feature of a true zero point, which represents the complete absence of the quantity being measured. This allows for the full range of arithmetic operations: addition, subtraction, multiplication, and division. Ratio data support summary statistics such as means, standard deviations, and coefficients of variation, and can be analyzed using the full suite of parametric methods, including regression analysis. Examples include body weight (kg), age (years), heart rate (beats per minute), and blood glucose level (mg/dL). Because of the true zero, it is meaningful to say that one animal weighs twice as much as another.

| **Scale** | **Ordering** | **Equal intervals** | **True zero** | **Valid operations** |
|---|:---:|:---:|:---:|---|
| Nominal | ✖ | ✖ | ✖ | Counting only |
| Ordinal | ✔ | ✖ | ✖ | Ranking, medians |
| Interval | ✔ | ✔ | ✖ | Subtraction, averaging |
| Ratio | ✔ | ✔ | ✔ | All (add, subtract, multiply, divide) |

## Scale vs. data type

It is important to distinguish scales of measurement from general data types, such as categorical, numerical, discrete, or continuous. Scales of measurement describe how variables are measured and interpreted, while data types refer to the structure or format of the values.

For example, categorical data typically correspond to nominal or ordinal scales, while numerical data are generally measured on an interval or ratio scale. However, a numeric-looking variable such as a pain score (e.g., 1, 2, 3) may still be ordinal if the distances between values are not consistent. Similarly, identification numbers or phone numbers, although composed of digits, are classified as nominal, since they are used as labels and have no mathematical meaning.

Understanding the distinction between scale and data type is essential for selecting appropriate statistical methods and ensuring valid interpretation of data in veterinary and biomedical research.