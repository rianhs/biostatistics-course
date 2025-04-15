# Measures of variability

**Measures of variability** (or **measures of dispersion**) are numerical summaries used in [descriptive statistics](descriptive-statistics.md) to describe the spread or dispersion of [data](data.md) within a dataset. They show how much individual observations differ from one another and from the central value, providing insight into the consistency or diversity of the data. The main measures—range, interquartile range, variance, and standard deviation—each capture a different aspect of variability and are chosen based on the type of data and its distribution. Understanding these measures is important for interpreting veterinary data, such as differences in body temperature among febrile animals, variation in daily milk production within a herd, or fluctuations in response to treatment. Recognizing the degree of variability helps assess data quality, compare populations, and support decision-making in veterinary research and clinical practice.

## Purpose and importance

While [measures of central tendency](measures-of-central-tendency.md) describe the typical or average value in a dataset, measures of variability show how much the values differ from each other. They provide essential context for understanding how data behave—whether the values are tightly clustered or widely spread out. This is critical for assessing the reliability, consistency, and biological relevance of results.

In veterinary medicine, variability can influence diagnosis, treatment, and management decisions. For example, if two herds of dairy cows have the same average milk production, but one herd shows a much wider variation, this could indicate nutritional inconsistencies, health problems, or differences in management practices. Measures of variability helps veterinarians and researchers understand not only the average condition of the animals, but also the predictability and stability of outcomes.

Without accounting for variability, conclusions based on averages alone may be misleading. Therefore, variability is a vital part of descriptive statistics and is essential for meaningful data interpretation in both clinical and research contexts.

## The range

The range is the simplest measure of variability. It is calculated by subtracting the smallest value from the largest value in a dataset:

<p style="text-align: center; font-size: 1.2em; font-style: italic; color: #34495E;">
  Range = Maximum value − Minimum value
</p>

It gives a quick sense of the total spread in the data. For example, suppose ten students in a veterinary biostatistics class scored the following on an exam (out of 100 points):

**Dataset A: 65, 68, 70, 71, 72, 73, 75, 77, 78, 80**

The highest score is 80, and the lowest is 65, so the range is 80 − 65 = 15

This indicates that all students scored within a 15-point span. The range reflects the total spread of scores, assuming no unusual values.

Now consider a second group of students where one individual performed far below the rest:

**Dataset B: 25, 68, 70, 71, 72, 73, 75, 77, 78, 80**

Here, the lowest score is 25, and the highest is still 80, so the range is 80 − 25 = 55

The range is much larger in this case because of a single outlier (score of 25). This very low value greatly increases the range and can may a misleading impression of overall variability. As this example shows, the range is very sensitive to outliers and should be interpreted with caution when the data set includes unusual values.

## The interquartile range

The interquartile range (IQR) measures the spread of the middle 50% of a dataset. It is defined as the difference between the third quartile (Q3) and the first quartile (Q1).

<p style="text-align: center; font-size: 1.2em; font-style: italic; color: #34495E;">
  IQR = Q₃ − Q₁
</p>

Quartiles are three values that divide ordered data into four equal parts:

- Q1 (lower quartile) is the value that marks the lower 25% of the data.
- Q2 (the median) is the middle value that divides the dataset in half.
- Q3 (upper quartile) is the value that marks the upper 75% of the data.

Q1, Q2, and Q3 are sometimes referred to as the 25th, 50th, and 75th percentiles, respectively.

The IQR describes the range within which the middle half of the data lies. Because it focuses on the middle values, the IQR is not affected by extreme values, making it a more robust measure than the range. Let's calculate the IQR for Dataset A and Dataset B.

**Dataset A: 65, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Step 1: Find the median (Q2). There are 10 values, so the median is the average of the 5th and 6th values. Q2 = (72 + 73) / 2 = 72.5
- Step 2: Find Q1 (lower quartile). It is the median of lower half (65, 68, 70, 71, 72). Q1 = 70
- Step 3: Find Q3 (upper quartile). It is the median of upper half (73, 75, 77, 78, 80). Q3 = 77
- Step 4: Calculate the IQR, which is Q3 − Q1 = 77 − 70 = 7

**Dataset B: 25, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Step 1: Find the median (Q2). There are 10 values, so the median is the average of the 5th and 6th values. Q2 = (72 + 73) / 2 = 72.5
- Step 2: Find Q1 (lower quartile). It is the median of lower half (25, 68, 70, 71, 72). Q1 = 70
- Step 3: Find Q3 (upper quartile). It is the median of upper half (73, 75, 77, 78, 80). Q3 = 77
- Step 4: Calculate the IQR, which is Q3 − Q1 = 77 − 70 = 7

Both datasets have an IQR of 7, meaning the central 50% of students scored within a 7-point range. However, Dataset B contains an outlier (score of 25), which increases the overall range but does not affect the IQR. This shows how the IQR is resistant to extreme values.

How is IQR calculated when the dataset contains an odd number of observations? Let’s look at Dataset C.

**Dataset C: 65, 68, 70, 71, 72, 73, 75, 77, 78, 80, 80**
- Step 1: Find the median (Q2). There are 11 values, so the median is the 6th values. Q2 = 73
- Step 2: Find Q1 (lower quartile). It is the median of lower half (first 5 values before the median, i.e. 65, 68, 70, 71, 72). Q1 = 70
- Step 3: Find Q3 (upper quartile). It is the median of upper half (last 5 values after the median, i.e. 75, 77, 78, 80, 80). Q3 = 78
- Step 4: Calculate the IQR, which is Q3 − Q1 = 78 − 70 = 8

In Dataset C, the IQR is 8. The increased upper quartile (Q3 = 78) reflects the presence of repeated high scores. This example also shows that when the number of observations is odd, the median (Q2) is excluded when forming the lower and upper halves to compute Q1 and Q3.

### Identifying outliers using IQR

The IQR is commonly used not only to measure variability but also to identify outliers, which are values ​​that fall far outside the typical range of the data. A widely used rule defines an outlier as any value that falls below the lower bound and above the upper bound.

<p style="text-align: center; font-size: 1.2em; font-style: italic; color: #34495E;">
  Lower bound = Q₁ − 1.5 × IQR
</p>

<p style="text-align: center; font-size: 1.2em; font-style: italic; color: #34495E;">
  Upper bound = Q₃ + 1.5 × IQR
</p>

Let’s apply this rule to both datasets to see how outlier detection works in practice.

**Dataset A: 65, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Q1 = 70
- Q3 = 77
- IQR = 7
- Lower bound = 70 − (1.5 x 7) = 70 − 10.5 = 59.5
- Upper bound = 77 + (1.5 x 7) = 70 − 10.5 = 87.5

All scores are within the range 59.5 to 87.5, so Dataset A has no outliers.

**Dataset B: 25, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Q1 = 70
- Q3 = 77
- IQR = 7
- Lower bound = 70 − (1.5 x 7) = 70 − 10.5 = 59.5
- Upper bound = 77 + (1.5 x 7) = 70 − 10.5 = 87.5

Here, the value 25 is below the lower bound of 59.5. All other values fall within the acceptable range. Therefore, 25 is an outlier.

This method allows researchers to identify unusually low or high values that may distort summaries or indicate exceptional cases. In veterinary biostatistics, outlier detection is valuable when examining results such as clinical measurements, production data, or biological test results—especially in situations where accurate interpretation of what is “typical” is essential for diagnosis, treatment, planning, or quality control. 

## The variance

Variance is a measure of how far individual values in a dataset are spread out from the mean. Unlike the range or the IQR, which describe overall or central spread, variance considers how each value deviates from the mean and then averages the squared differences. This approach gives a more detailed view of variability across all data points.

In statistical notation, different symbols are used for population and sample variance. Population variance is written as σ² and sample variance as  s². The formulas differ only in the denominator:

<center>
<img src="https://latex.codecogs.com/svg.image?\sigma^2=\frac{\sum(x_i-\mu)^2}{N}"   
     alt="Population variance formula"
     style="width: 150px; margin: 20px 0;">
</center>

<center>
<img src="https://latex.codecogs.com/svg.image?s^2=\frac{\sum(x_i-\bar{x})^2}{n-1}"   
     alt="Sample variance formula"
     style="width: 150px; margin: 20px 0;">
</center>

Where
- σ² = population variance
- s² = sample variance
- Σ = summation symbol, indicating that values are to be added together
- 𝑥ᵢ = each individual value
- μ = population mean
- 𝑥̅ = sample mean 
- 𝑁 = population size
- 𝑛 = sample size

Each deviation from the mean is squared to ensure all values are positive and to give more weight to larger differences. The sample formula uses 𝑛 − 1 in the denominator (instead of 𝑛) to correct for bias when estimating population variability from a sample—this adjustment is known as Bessel’s correction. In veterinary biostatistics, the sample formula is most commonly used. 

To illustrate, consider the biostatistics exam datasets:

**Dataset A: 65, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Mean (𝑥̅) = 72.9
- Sample variance (s²) ≈ 21.88

**Dataset B: 25, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Mean (𝑥̅) = 68.9
- Sample variance (s²) ≈ 252.1

This comparison shows how a single outlier (score of 25 in Dataset B) drastically increases the variance, indicating much greater spread in the data. While Dataset A shows relatively consistent scores, Dataset B contains more variability due to the extreme value.

Although variance is mathematically important, its units are squared (e.g., points²), which makes it harder to interpret directly. For this reason, variance is most often used as an intermediate step in calculating the standard deviation.

## The standard deviation

The standard deviation is the most widely used measure of variability in scientific and clinical work. It is defined as the square root of the variance:

<center>
<img src="https://latex.codecogs.com/svg.image?\sigma=\sqrt{\sigma^2}"   
     alt="Population standard deviation"
     style="width: 80px; margin: 20px 0;">
</center>

<center>
<img src="https://latex.codecogs.com/svg.image?s=\sqrt{s^2}"   
     alt="Sample standard deviation"
     style="width: 80px; margin: 20px 0;">
</center>

Unlike variance, the standard deviation is expressed in the same units as the original data, making it easier to interpret and compare.

Continuing with the previous example:

**Dataset A: 65, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Mean (𝑥̅) = 72.9
- Sample variance (s²) = 21.88
- Sample standard deviation (s) = √21.88 = 4.68

**Dataset B: 25, 68, 70, 71, 72, 73, 75, 77, 78, 80**
- Mean (𝑥̅) = 68.9
- Sample variance (s²) = 252.1
- Sample standard deviation (s) = √252.1 = 15.88

This comparison shows how an outlier increases the standard deviation, reflecting greater variability. Dataset A has a tight grouping of scores, with most students scoring near the mean. In contrast, Dataset B includes one very low score, resulting in a much wider spread. The standard deviation captures this difference clearly.

The standard deviation provides a concise summary of variability and is particularly useful when the data are approximately normally distributed. In such cases, about 68% of values fall within one standard deviation of the mean, and about 95% fall within two standard deviations. These properties make the standard deviation especially helpful when interpreting laboratory values, physiological measurements, and production metrics.

In veterinary practice, standard deviation is widely used to assess biological consistency or variation. For example:

- In a herd of dairy cows, a high standard deviation in daily milk production may indicate inconsistent feeding, undiagnosed health issues, or variable environmental conditions.

- In a study of rectal temperatures in cats, a low standard deviation may suggest similar physiological responses across individuals.

### Reporting mean ± standard deviation

In veterinary studies and scientific writing, the standard deviation is often reported alongside the mean using the format:

<center>Mean ± Standard Deviation</center>

This notation provides a quick impression of both the central value and the typical spread of the data. For example:

- Dataset A: 72.9 ± 4.68
- Dataset B: 68.9 ± 15.88

This format is widely used when reporting clinical, physiological, or laboratory results. It helps readers evaluate both the typical case and the extent of variability within the sample. Note that while the sample standard deviation uses 𝑛 − 1, the population standard deviation uses 𝑛 in the denominator. Understanding this difference is important when interpreting summary statistics in different study designs. 

While more complex to compute than the range or the IQR, the standard deviation combines sensitivity to all data points with interpretability, making it one of the most important tools in descriptive statistics.

## Choosing the appropriate measure

Choosing the right measure of variability depends on the scale of measurement, the distribution of the data, and the purpose of the analysis. Each measure is suited to particular types of data.

- Nominal data (e.g., breed, disease category): Traditional variability measures such as range, IQR, variance, and standard deviation do not apply, since nominal categories cannot be ordered or meaningfully quantified. Instead, variability is typically described using frequencies or proportions.

- Ordinal data (e.g., lameness scores, pain severity): Use the IQR to capture the central spread while respecting the order of values. The range can also be used but is sensitive to outliers. Variance and standard deviation are generally not appropriate unless the distances between categories are meaningful and consistent.

- Interval and ratio data (e.g., body temperature, heart rate, milk production): Use the standard deviation if the data are symmetrical and approximately normally distributed. Use the IQR if the data are skewed or contain outliers. The range can provide a quick overview but may be misleading in the presence of extreme values.

When selecting a measure, it's also important to understand the trade-offs involved:

- The range is easy to compute but highly sensitive to outliers.
- The IQR provides a stable summary that resistant to outliers and good for non-normal data.
- The variance offers mathematical precision but is harder to interpret due to its squared units.
- The standard deviation combines sensitivity and interpretability and is widely used in veterinary research.

For example, if blood pressure values in cats are symmetrically distributed, the mean ± standard deviation provides an informative summary.  If the data are skewed or contain extreme values, the median and IQR offer a clearer, more robust description. No single measure is best in all situations. The key is to match the measure to the data and the question being asked—ensuring that veterinary findings are summarized accurately and communicated clearly.

## Applications in veterinary practice

Measures of variability are used throughout veterinary science, including clinical care, research, diagnostics, and herd health management. They provide essential context for interpreting averages and support more informed decision-making.

- In herd health, variability helps detect management issues. Two herds of dairy cows may have the same average milk production but different standard deviations. The herd with higher variability may have inconsistent feeding, subclinical disease, or uneven environmental conditions.

- In clinical studies, variability informs how consistent treatment effects are. A drug that produces consistent fever reduction (low standard deviation) may be more desirable than a drug with the same mean effect but wide variability. Similarly, reporting the IQR of wound healing times can help veterinarians and clients set realistic expectations.

- In diagnostic testing, identifying high variability in liver enzyme levels in a group of animals, for example, s may prompt further investigation into environmental exposures or genetic predispositions.

- In epidemiology, knowing whether a condition shows narrow or wide variation can guide decisions on sampling, biosecurity, or intervention strategies.

Measures of variability also play a key role in communicating results to stakeholders. Farmers, pet owners, and policy-makers may understand that the “average” result is not the whole story. Showing the spread of values—using standard deviation or IQR—clarifies whether a reported result is typical or highly variable. In all of these contexts, measures of variability are more than just technical calculations. They are essential tools for understanding, interpreting, and applying veterinary data in real-world settings.