# Measures of central tendency

**Measures of central tendency** are numerical summaries used in [descriptive statistics](descriptive-statistics.md) to identify the central or typical value within a dataset. They provide a concise way to describe where data points cluster, offering insight into the most representative observation. The three main measures—mean, median, and mode—each capture a different aspect of central tendency and are selected based on the type of data and its distribution. Understanding these measures is essential for interpreting veterinary data, such as the average birth weight of calves, the median recovery time after treatment, or the most frequently observed clinical sign in a disease outbreak. Choosing the appropriate measure helps summarize data meaningfully and supports further statistical analysis.

## Purpose and importance

Measures of central tendency are essential for summarizing data by identifying the value around which observations tend to cluster. They help researchers and practitioners quickly understand the "typical" case in a dataset, supporting comparison, interpretation, and communication. In veterinary contexts, these measures are often used to describe key characteristics—such as the average daily weight gain in livestock, the median duration of treatment recovery, or the most common clinical sign observed in a group of patients. Without such measures, large datasets may remain confusing or difficult to interpret. By simplifying complex data into meaningful summaries, measures of central tendency provide a foundation for reporting, analysis, and evidence-based decision-making.

## The mean

The mean, or average, is the most commonly used measure of central tendency. It is calculated by adding all values in a dataset and dividing by the number of observations. For a dataset with 𝑛 values 𝑥₁, 𝑥₂, 𝑥₃, ..., 𝑥ₙ, the formula is:

<center><img src="https://latex.codecogs.com/svg.image?\bar{x}=\frac{x_1+x_2+\cdots+x_n}{n}" alt="mean formula"></center>

The mean provides a single numerical summary that reflects the overall level of the data. For example, if a veterinarian records the weights of five calves as 25.0, 27.5, 26.0, 25.5, and 40.0 kg, the mean weight is 28.8 kg. However, this value is strongly influenced by the unusually heavy calf (40.0 kg), which does not reflect the rest of the group.

This sensitivity to extreme values (called outliers) is a key limitation of the mean. When data are symmetrically distributed, the mean is a reliable and efficient summary. However, in skewed distributions or when outliers are present, the mean can be misleading. In such cases, the median may offer a more accurate picture.

The mean is best suited to interval and ratio scale data, where arithmetic operations such as addition and division are meaningful.

## The median

The median is the middle value of a dataset when the values are arranged in order. It divides the data into two equal parts: 50% of the values fall below the median and 50% fall above it. If the number of observations is odd, the median is the central value. If the number is even, the median is the average of the two central values.

For example, consider a study that records the rectal temperatures (in °C) of seven cats: 37.8, 38.0, 38.2, 38.3, 38.4, 38.5, and 39.0. The median is 38.3 °C—the fourth value in the ordered list. If one cat had an unusually high temperature (e.g., 41.5 °C), the median would stay the same, while the mean would increase.

This resistance to outliers and skewed data makes the median particularly useful when the distribution is not symmetrical or when data are ordinal. For example, when evaluating pain scores or body condition scores in animals, the median often provides a better summary than the mean. The median is appropriate for ordinal, interval, and ratio data, especially when the data are not normally distributed.

## The mode

The mode is the value that appears most frequently in a dataset. Unlike the mean and median, it does not depend on the size of the values but on how often they occur. A dataset may have no mode (if all values are different), one mode (unimodal), or more than one mode (bimodal or multimodal).

For example, if a veterinarian records the number of puppies in eight litters as 4, 5, 5, 6, 7, 5, 8, and 4, the mode is 5—indicating that litters of five puppies were the most common.

The mode is especially useful for categorical data, such as coat color, breed, or type of disease. For example, identifying the most frequently diagnosed parasitic infection in a group of animals provides insight into common health problems without requiring numerical calculations. The mode can be used with nominal, ordinal, interval, and ratio data. However, it is most commonly applied to nominal and ordinal variables, where the mean and median are not meaningful.

## Comparing mean, median, and mode

Although the mean, median, and mode all aim to describe the center of a dataset, they differ in how they do so and in the types of data they are best suited for. The mean reflects the arithmetic average and works best when data are symmetrically distributed without extreme values. The median identifies the middle position and is more resistant to outliers, making it more suitable for skewed data or for variables measured on an ordinal scale. The mode shows the most frequently occurring value and is particularly helpful for nominal data or when identifying the most common category is the main goal.

These differences can be illustrated with an example. Suppose the weights (in kg) of five sheep are recorded as: 40, 42, 43, 45, and 70. The mean is 48 kg, pulled upward by the unusually heavy individual. The median is 43 kg, which better reflects the central value for most of the group. The mode is undefined, as no value occurs more than once. In this case, the median provides the most meaningful summary.

Understanding the relationship among these measures also helps in identifying skewness in the data. When the mean is greater than the median, the distribution is typically right-skewed (positive skew). When the mean is less than the median, the data are left-skewed (negative skew). If all three values are close together, the distribution is likely symmetrical.

## Choosing the appropriate measure

Choosing the right measure of central tendency depends on several factors, including the scale of measurement, the shape of the distribution, and the objective of the analysis. Each measure is suited to particular types of data:

- For nominal data (e.g., species, coat color), only the mode is appropriate, since the values cannot be ordered or averaged.
- For ordinal data (e.g., pain scores, disease stages), the median is preferred because it respects the natural order of the data without assuming equal spacing between values.
- For interval and ratio data (e.g., temperature, weight, heart rate), the mean is suitable when the data are symmetrically distributed and free from outliers. If the data are skewed or contain extreme values, the median offers a more reliable summary.

In veterinary contexts, using the wrong measure can lead to misleading interpretations. For example, reporting the mean recovery time after surgery might be distorted by one animal with an unusually long complication. In this case, the median would provide a better representation of the general results.

The choice of measure also depends on the purpose of the analysis. If the goal is to estimate overall population characteristics or to use the data in mathematical models, the mean may be more appropriate. If the aim is to communicate typical results in non-normal data, the median is often more informative and easier to interpret.

## Applications in veterinary practice

Measures of central tendency are routinely used in veterinary medicine to support clinical decision-making, epidemiological analysis, and animal health management. For instance, calculating the average daily feed intake in a group of pigs can help assess nutrition programs, while identifying the median recovery time after treatment informs realistic expectations for healing.

In herd health surveillance, the mode may reveal the most common disease condition across farms, helping veterinarians prioritize prevention and control strategies. In diagnostic studies, reporting the median biomarker value can offer a clearer picture of disease status, especially when data are highly variable or skewed.

These measures also play a key role in communicating findings to others—whether it be farmers, pet owners, or policy-makers. For example, reporting the average milk production per cow or the typical calving interval helps transform data into information that can guide action.

Ultimately, measures of central tendency are more than just mathematical concepts. When used appropriately, they become essential tools for interpreting data, informing decisions, and improving outcomes in veterinary science and practice.