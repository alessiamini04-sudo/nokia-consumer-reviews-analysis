# Nokia Consumer Reviews Analysis

**Overview**

This project provides a Python-based analysis of consumer reviews of Nokia smartphones and selected iPhone models.

The project builds on a previous psychological case study of Nokia's decline, which examined cognitive biases, organizational decision-making and resistance to technological change. Here, the original qualitative perspective is complemented with a quantitative, consumer-level analysis of online review data.

The aim is not to explain the causes of Nokia's decline, but to investigate how consumers evaluated different Nokia smartphone families and how these evaluations compared with iPhone products during a comparable observation period.

**Research Questions**

The analysis addresses three main questions:

1. How do consumer ratings differ across Nokia smartphone families?
2. How do Nokia Lumia, Nokia X and iPhone ratings compare when using a comparable observation period?
3. Are the observed differences robust when repeated reviews from the same users are taken into account?

**Dataset**

The original dataset contains consumer reviews from nine mobile phone brands.

After combining and cleaning the source files:

- 161,192 original reviews
- 159,591 reviews after removing exact duplicates
- Review period: 2011–2017
- 19,198 Nokia reviews
- 12,540 iPhone reviews

Because Nokia and iPhone reviews were unevenly distributed across years, the main comparative analysis focuses on **2015**, where the three smartphone groups had similar review coverage.

Final comparison sample:

- Nokia Lumia: 428 reviews
- Nokia X: 428 reviews
- iPhone: 439 reviews
- Total: 1,295 reviews

**Methods**

The project includes:

- Data cleaning and validation
- Exploratory data analysis
- Temporal analysis of review coverage
- Smartphone product-family classification
- Descriptive statistics
- Model-level comparisons
- Kruskal-Wallis non-parametric tests
- User-level robustness analysis
- Bootstrap confidence intervals
- Data visualization with Matplotlib

**Main Findings**

In the balanced 2015 comparison sample, Nokia Lumia, Nokia X and iPhone showed relatively similar overall consumer evaluations.

The review-level Kruskal-Wallis test did not identify statistically significant differences between the three smartphone groups.

A second analysis aggregated multiple reviews from the same consumer so that each reviewer contributed one observation. The conclusions remained similar, suggesting that the main result was not driven by repeated reviewers.

The analysis also revealed substantial variation between individual smartphone models, showing that brand-level averages can hide meaningful differences within the same product portfolio.

**Interpretation**

The findings suggest that consumer evaluations in the observed 2015 sample cannot be reduced to a simple Nokia-versus-iPhone distinction.

Instead, consumer responses varied across specific smartphone families and models. This provides a consumer-level complement to the original psychological case study of Nokia's strategic difficulties.

The results should not be interpreted as evidence about the causes of Nokia's market decline.

**Limitations**

Several limitations should be considered:

- Online reviews are observational data and are not representative of all smartphone consumers.
- The dataset does not cover Nokia's initial response to the introduction of the iPhone in 2007.
- The main comparison is restricted to 2015 because this year provides the most balanced review coverage.
- Some product families are represented by substantially more reviews than others.
- Ratings capture overall consumer evaluations but do not directly measure the psychological or organizational mechanisms discussed in the original case study.

**Tools**

- Python
- pandas
- NumPy
- SciPy
- Matplotlib
- Google Colab

**Project File**

The complete analysis, code, outputs and visualizations are available in:

`Nokia_Consumer_Reviews_Data_Analysis.ipynb`
