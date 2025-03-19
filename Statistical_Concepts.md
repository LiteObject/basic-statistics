# Statistics Concepts Overview

## Introduction to Statistics
- Aims to provide an intuitive understanding of statistics without mathematical complexity
- Suitable for beginners or those apprehensive about quantitative analysis
- Uses universal examples for practical context

---

## Types of Data
### Categorical Data
- Represents groups or labels
- Subtypes:
  - **Nominal**: No inherent order (e.g., colors, types of fruit)
  - **Ordinal**: Ordered categories (e.g., education levels: high school, bachelor's, PhD)

### Numerical Data
- Represents measurable quantities
- Subtypes:
  - **Discrete**: Countable values (e.g., number of pets in a household)
  - **Continuous**: Infinitely divisible measurements (e.g., temperature, weight)

### Proportions & Percentages
- Percentages are proportions scaled to 100
- Derived from categorical data (e.g., survey responses: 60% "yes", 40% "no")
- Philosophical question: Whether proportions should be classified as discrete or continuous

---

## Distributions
- Probability density functions describe how data values are spread
- Common types:
  - **Normal Distribution**: Symmetrical bell curve (e.g., human height distribution)
  - **Uniform Distribution**: Equal likelihood across range (e.g., rolling a fair die)
  - **Bimodal Distribution**: Two distinct peaks (e.g., adult shoe sizes combining men's and women's distributions)
  - **Skewed Distribution**: Asymmetrical with tail (e.g., income distribution)

---

## Sampling Distributions
- Probability distribution of sample statistics (e.g., average exam scores in multiple class samples)
- Key properties:
  - Matches population mean
  - Tighter spread than population data
  - Larger samples reduce extreme averages
- Foundation for drawing conclusions about populations

---

## Sampling & Estimation
- **Sample Statistic**: Calculated from sample data (e.g., average commute time from 100 city residents)
- **Population Parameter**: Fixed values described by Greek letters:
  - θ (general parameter)
  - μ (population mean)
  - σ (standard deviation)
  - π (proportion)
  - ρ (correlation)
  - β (regression coefficient)
- Estimates always include uncertainty

---

## Confidence Intervals
- Plausible range for population parameter (e.g., "We're 95% confident the true average is between 25-30")
- Features:
  - Sample estimate at center
  - Wider intervals indicate more uncertainty
  - Halving uncertainty requires quadrupling sample size

---

## Hypothesis Testing
### Key Components
- **Null Hypothesis (H₀)**: Default assumption (e.g., "New medication = placebo effect")
- **Alternate Hypothesis**: Research claim (e.g., "Medication > placebo")
- **Significance Level (α)**: 5% probability threshold

### Process
- Calculate probability of observed data *if H₀ were true*
- Reject H₀ only if evidence is sufficiently strong (p < α)
- Never "accept" hypotheses - only assess evidence strength

---

## P-Values
- Probability of seeing results *at least as extreme* as observed, assuming H₀
- **Example**: p = 0.03 means 3% chance of observed effect if H₀ is true
- Not the probability that H₀ is true/false

---

## P-Hacking
- Misleading practices to achieve statistical significance
- Common forms:
  - Testing numerous unrelated hypotheses
  - Removing "outliers" selectively
  - Changing analysis methods post-data collection
- Increases false discoveries; emphasizes need for pre-registered studies
