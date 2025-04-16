# Inferential statistics

**Inferential statistics** is a branch of [statistics](statistics.md) that uses data from a [sample](sample.md) to make predictions, generalizations, or conclusions about a larger [population](population.md). Unlike [descriptive statistics](descriptive-statistics.md), which summarize data that have already been collected, inferential statistics rely on probability theory to estimate population characteristics and test hypotheses. The aim is to make informed judgments under uncertainty, using data from a smaller group that represents the whole. In veterinary research, for example, it is often impractical or impossible to collect data from every animal in a population. Instead, researchers may examine a sample—such as 100 cows from a particular region—and use inferential techniques to estimate disease prevalence, evaluate treatment effects, or identify risk factors that apply to the broader population.

## Estimating population parameters

One of the main goals of inferential statistics is to estimate unknown values in a population (called [parameters](parameter.md)) using known values calculated from a sample (called [statistics](statistic.md)). A common example is using the sample mean to estimate the population mean.

These estimates may be reported as single values (called point estimates) or as ranges that express uncertainty (called interval estimates). For example, if the average body temperature in a sample of cats is 38.3 °C, this single value is the point estimate of the population mean. An interval estimate might report that the 95% confidence interval for the average temperature range from 38.1 °C to 38.5 °C. This means that, based on the sample and the method used, we can be reasonably confident that the true population mean lies within that interval.

The width of a confidence interval depends on the sample size and the variability in the data. Larger samples and more consistent data usually lead to narrower, more precise intervals. Estimation plays a key role in many areas of veterinary science, including epidemiology, diagnostics, and treatment studies, where collecting data from the entire population is often unfeasible.

## Hypothesis testing

Another major function of inferential statistics is hypothesis testing. It is a process used to determine whether the data provide enough evidence to support or reject a specific claim about a population.

The process begins with formulating two opposing hypotheses: the null hypothesis (which typically represents no effect or no difference) and the alternative hypothesis (which represents the presence of an effect or difference). For example, the null hypothesis might state that there is no difference in average weight gain between two types of feed, while the alternative hypothesis suggests that there is a difference.

A numerical test statistic is then calculated from the sample data, and a p-value is used to determine how likely the observed result would be if the null hypothesis were true. A small p-value (commonly less than 0.05) suggests that the result would be unlikely under the null hypothesis, offering support for the alternative hypothesis. 

However, a p-value does not measure the size or importance of an effect, and results must always be interpreted in context. Proper hypothesis testing also requires understanding Type I error (rejecting a true null hypothesis) and Type II error (failing to reject a false one), as well as considering how factors like sample size and study design influence the test’s ability to detect real effects. 

## Statistical tests

Statistical tests are procedures used to determine whether patterns observed in a sample are likely to reflect true differences or relationships in the larger population. These tests are generally grouped into two categories: those that assess differences between groups (such as comparing averages or proportions) and those that examine relationships between [variables](variable.md) (such as correlations or associations).

Each statistical test relies on certain assumptions about the data. Parametric tests assume that the data follow a specific distribution—typically a normal (bell-shaped) distribution—and meet other conditions such as equal variances across groups. When these assumptions are met, parametric tests are used because they are generally more statistically powerful. Non-parametric tests, on the other hand, do not require such assumptions. They are useful when dealing with ordinal data, skewed distributions, or datasets with outliers that would violate the assumptions of parametric tests.

The table below provides an overview of common statistical tests, organized by the [scales of measurement](scales-of-measurement.md) and the type of analysis being conducted.

<div class="centered-table">
  <table>
    <thead>
      <tr>
        <th rowspan="3">Scales of Measurement</th>
        <th colspan="3">Purpose of Statistical Test</th>
      </tr>
        <th colspan="2">Test Differences</th>
        <th rowspan="2">Examine Relationships</th>
      </tr>
      <tr>
        <th>Two Groups</th>
        <th>More Than Two Groups</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Nominal</b></td>
        <td>Chi-square tests<br><br>Fisher’s exact test</td>
        <td>Chi-square tests</td>
        <td>Chi-square tests<br><br>Cramér’s V<br><br>Phi coefficient</td>
      </tr>
      <tr>
        <td><b>Ordinal</b></td>
        <td>Mann–Whitney U test<br><br>Wilcoxon rank-sum test</td>
        <td>Kruskal–Wallis test</td>
        <td>Correlation (Spearman)</td>
      </tr>
      <tr>
        <td><b>Interval</b></td>
        <td>t-tests*<br><br>Mann–Whitney U test<br><br>Wilcoxon signed-rank test</td>
        <td>ANOVA-based tests*<br><br>Kruskal–Wallis test</td>
        <td>Correlation tests (Pearson*/Spearman)<br><br>Regression models*</td>
      </tr>
      <tr>
        <td><b>Ratio</b></td>
        <td>t-tests*<br><br>Mann–Whitney U test<br><br>Wilcoxon signed-rank test</td>
        <td>ANOVA-based tests*<br><br>Kruskal–Wallis test</td>
        <td>Correlation tests (Pearson*/Spearman)<br><br>Regression models*</td>
      </tr>
    </tbody>
  </table>
    <div class="table-note">
    <em>* = parametric test</em>
  </div>
</div>

<style>
  .centered-table table {
    width: 100%;
    border-collapse: collapse;
    margin: 0 0 4px 0;
  }

  .centered-table th,
  .centered-table td {
    border: 1px solid #ccc;
    padding: 8px 12px;
  }

  .centered-table th {
    background-color: #f5f5f5;
  }

    .centered-table .table-note {
    font-size: 0.9em;
    color: #444;
    margin-top: 0;
    padding-top: 0;
  }
</style>

Each statistical test has its own assumptions, advantages, and limitations. Choosing the right method depends on the research question, the type and scale of the variables, the shape of the data distribution, and whether the assumptions for parametric tests can be met.

Visualizing inference
Although data visualization is often associated with descriptive statistics, it also plays a valuable role in inferential analysis. Visual tools can help communicate uncertainty, effect size, and statistical significance.

For example, confidence intervals are often represented as error bars on bar graphs or line charts, making it easier to compare groups and interpret overlap. Sampling distributions can be plotted to illustrate concepts like standard error and the range of likely sample outcomes under the null hypothesis. Some reports also use p-value visualizations, such as shaded areas under curves or symbolic markers (like asterisks), to indicate levels of significance—though these should be interpreted carefully and in context.

Effective visualization enhances understanding and transparency. It helps bridge the gap between statistical analysis and practical interpretation, especially in fields such as veterinary medicine where findings inform clinical or policy decisions.

## Role in statistical practice

Inferential statistics plays a central role in research, public health, and clinical decision-making. It allows researchers to extend insights from a sample to a broader population and to evaluate the likelihood that observed differences or associations reflect real effects, rather than random variation.

In veterinary contexts, inferential methods are used to test the effectiveness of new treatments, estimate the prevalence of diseases, assess risk factors, and evaluate the impact of interventions. For example, a study might use a sample of farms to estimate national disease prevalence, or compare outcomes before and after a vaccination program. These results inform real-world actions, such as modifying herd management practices or developing disease control strategies.

Ultimately, inferential statistics supports evidence-based reasoning under uncertainty When applied with proper study design, sound methodology, and careful interpretation, it transforms sample data into meaningful conclusions that support science and improve practice.