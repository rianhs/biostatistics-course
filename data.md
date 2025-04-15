# Data

**Data** are values that represent specific concepts or phenomena and can be [collected](data-collection.md), [organized](data-organization.md), [analyzed](data-analysis.md), [interpreted](data-interpretation.md), and [presented](data-presentation.md) to derive meaningful information. These values serve as simplified representations of reality, allowing researchers and practitioners to observe patterns, measure differences, and make informed decisions. In the context of statistical reasoning, data are the raw material from which evidence is drawn. Although data alone do not carry inherent meaning, they acquire significance when placed within a context and examined through appropriate methods.

## Types and structures

Data can be classified in multiple ways, depending on their nature and how they are recorded or processed. One of the most fundamental distinctions is between categorical (qualitative) data and numerical (quantitative) data. Categorical data represent characteristics, groupings, or labels—such as species, disease status, or treatment type. These can be further divided into nominal data, which consist of unordered categories, and ordinal data, where the categories have a meaningful order or ranking. Numerical data, by contrast, represent measurable quantities and are expressed as numbers. These can be further classified as discrete data, which consist of countable values (such as the number of offspring), or continuous data, which can take on any value within a range (such as body weight or temperature).

| **Type of Data** | **Definition** | **Examples**  |
|---|---|---|
| **Categorical (qualitative)** | A type of data that represents categories or groups, usually expressed as names or labels. | |
| &nbsp;&nbsp;– Nominal | Categories with no natural order or ranking. | Species, coat color, vaccination status |
| &nbsp;&nbsp;– Ordinal | Categories with a meaningful order, but without consistent intervals among them. | Body condition score, pain severity scale, disease stage |
| **Numerical (quantitative)** | A type of data that represents measurable quantities, expressed as numbers. | |
| &nbsp;&nbsp;– Discrete | Numeric values that can only take on specific and separate values, such as whole numbers, and is typically counted rather than measured. | Number of offspring, number of visits, tick counts |
| &nbsp;&nbsp;– Continuous | Numeric values that can take on any value within a range, including decimals and fractions, and is typically measured rather than counted. | Body temperature, weight, blood glucose level |


Another important classification concerns the structure of data—how they are formatted and stored. Unstructured data lack a predefined organization and may include free-text clinical notes, diagnostic images, audio recordings, or raw sensor outputs. These data are often collected in their natural form and must be preprocessed or transformed before analysis.

In contrast, structured data are organized into clearly defined formats, such as spreadsheets, databases, or coded forms, where variables and records are systematically arranged. Structured data allow for more efficient analysis, particularly when using statistical software. In modern veterinary and biomedical research, both structured and unstructured data are common. However, unstructured data increasingly require specialized tools and computational methods to extract useful information.

## Within the statistical process

In statistical practice, data play a central role at every stage of the process. During collection, data are gathered through observation, measurement, or experimentation. Organization involves arranging the data systematically—such as entering values into a table or database—and addressing issues like coding, formatting, and error correction.

Once organized, the data are ready for analysis, where statistical methods are applied to identify patterns, relationships, or trends. This is followed by interpretation, in which meaning is derived from the results, typically in relation to a research question or hypothesis. Finally, presentation involves communicating the findings clearly and accurately, often using text, tables, or visualizations. Each of these steps depends on the quality, structure, and relevance of the data involved.

## DIKW pyramid

The DIKW (data, information, knowledge, and wisdom) pyramid is a conceptual framework that illustrates how raw data are progressively transformed into information, knowledge, and ultimately wisdom. It emphasizes increasing levels of interpretation, understanding, and informed decision-making as data are processed within a given context.

<div style="text-align: center;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/DIKW_Pyramid.svg" 
       alt="DIKW Pyramid"
       style="width:35%; display: block; margin: auto;">
  <p>
    <em>Figure: The DIKW Pyramid (source: 
      <a href="https://commons.wikimedia.org/wiki/File:DIKW_Pyramid.svg" target="_blank">Wikimedia Commons</a>)
    </em>
  </p>
</div>

At the base of the pyramid is data—raw, unprocessed values that have limited meaning on their own. For example, a veterinarian records the rectal temperatures of 100 dairy cows during a routine herd check. These individual measurements, without further context, are simply data.

When the veterinarian organizes and analyzes these readings—calculating the average, identifying abnormal values, and linking them to individual animals—the data become information. The herd’s average temperature and the identification of five cows with elevated readings now offer a clearer picture of the herd’s health status.

Knowledge emerges when this information is interpreted through experience and contextual understanding. The veterinarian recognizes that elevated temperatures, along with recent changes in feed and mild respiratory symptoms, are consistent with a suspected outbreak of bovine respiratory disease (BRD). This diagnosis is informed not only by data, but by domain knowledge and pattern recognition.

Finally, wisdom involves applying this knowledge to make sound, ethical, and forward-looking decisions. In this case, the veterinarian not only treats the affected animals but also advises the farmer on preventive strategies, such as improving ventilation and revising vaccination protocols to prevent future outbreaks. These actions reflect judgment, foresight, and an awareness of both animal welfare and long-term herd health.

The DIKW model emphasizes that data alone are not enough. Their true value depends on how they are interpreted and applied in real-world contexts. In veterinary medicine, this model supports evidence-based practice by promoting critical thinking across all levels of data use.

## Sources

Data can originate from many different sources, depending on the goals and design of a study. A fundamental distinction is between primary data and secondary data. Primary data are collected directly by the investigator for a specific purpose, using methods such as measurements, surveys, interviews, or laboratory testing. Secondary data, by contrast, are previously collected for other purposes and later repurposed for new analysis. Although secondary data can be time-saving and resource-efficient, they often require critical evaluation for accuracy, relevance, and completeness.

Data may also be classified based on the type of study in which they are collected. In observational studies, researchers gather data without intervening in the system being studied. The goal is to observe and analyze phenomena as they occur naturally. Examples include cross-sectional surveys of disease prevalence, retrospective analysis of medical records, or field studies examining environmental exposure. Observational studies are particularly common in veterinary epidemiology, where direct manipulation of variables may be impractical or unethical.

In contrast, experimental studies involve the intentional manipulation of one or more variables to observe their effects on outcomes. This is typically done in controlled environments, such as assessing the efficacy of a new vaccine, evaluating feed additives in livestock, or testing treatment protocols for common diseases. These studies often use randomization, control groups, and blinding to reduce bias and increase the reliability of findings.

## Limitations and ethical considerations

Despite their value, data are subject to important limitations that can affect the reliability of statistical analysis. Common issues include missing values, measurement errors, and inaccurate recording. All of them can compromise the validity of results. In addition, bias may be introduced at any stage—from sampling and data collection to analysis and interpretation— especially when data are not representative or when collection methods vary across cases.

Working with data also raises a number of ethical considerations. These include protecting confidentiality, especially when records contain identifiable information about animal owners, farms, or clinics. Responsible data use requires clear protocols for access, sharing, and storage. In research contexts, ethical review processes help ensure that data are collected in ways that respect animal welfare and that findings are reported honestly and transparently. 

## Emerging trends and technologies

Advancements in technology have transformed how data are collected, managed, and analyzed. The rise of big data—characterized by large volume, high velocity, and diverse variety— has introduced new opportunities and challenges. In veterinary science, big data may come from large-scale genomic studies, real-time disease surveillance systems, or aggregated electronic health records. 

Modern data sources increasingly rely on automated technologies, such as barn sensors, wearable tracking devices, and remote monitoring systems. These tools can capture detailed, continuous data on animal movement, behavior, temperature, feeding patterns, and environmental conditions. Similarly, digital imaging and video-based systems generate large volumes of unstructured data that can be used for diagnostics and welfare monitoring.

To make sense of these complex datasets, researchers are turning to machine learning and artificial intelligence. These methods allow for the detection of subtle patterns, prediction of outcomes, and classification of cases—often beyond the capacity of traditional statistical techniques. However, these technologies must be used with caution. Their effectiveness depends on data quality, appropriate modeling, and a strong foundation in statistical thinking. Without careful oversight, algorithmic models risk producing misleading or biased results.