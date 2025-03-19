# About Statistics

## Fundamentals of Data
- **Data Types**: 
  - **Quantitative data** (numbers) vs **Qualitative data** (words)
  - **Discrete data** (integers) vs **Continuous data** (entire number line)
  - Special types include binary data (0/1), categorical data, count data, and time-to-event data

## Probability Theory
- **Random Variables**: Representations of data that can take different values with different probabilities
  - Usually represented by capital letters (variables) and lowercase letters (actual values)
- **Probability Distributions**: Functions that describe the probabilities associated with values
  - **PDF** (Probability Density Function) or **PMF** (Probability Mass Function)
  - **CDF** (Cumulative Distribution Function) - useful for defining quantiles and percentiles
- **Common Distributions**:
  - Uniform distribution (all values equally likely)
  - Bernoulli distribution (binary data)
  - Binomial distribution (multiple successes)
  - Poisson distribution (counts)
  - Normal distribution (bell shape, widely used)

## Descriptive Statistics
- **Measures of Central Tendency**:
  - Mean (expectation/expected value)
  - Median (middle value)
  - Mode (most common value)
- **Measures of Scale**:
  - Variance (how far values can be from expected value)
  - Standard deviation (spread of data in original units)
- **Measures of Shape**:
  - Skewness (imbalance in distribution)
  - Kurtosis (pointiness of distribution)

## Inferential Statistics
- **Population vs Sample**: We study samples to infer about populations
- **Statistical Models**: Assumptions about how data was generated
- **Parameters**: Unknown values in these models we aim to estimate
- **Estimators**: Guesses for parameters based on collected data
  - Sample mean is a common estimator with good properties
- **Law of Large Numbers**: Sample mean approaches population mean with enough data
- **Central Limit Theorem**: Sample means follow normal distribution with enough data
- **Sampling Distribution**: The distribution of an estimator

## Hypothesis Testing
- **Null Hypothesis**: Belief about the world we want to disprove
- **Alternative Hypothesis**: Opposes the null
- **P-value**: Probability of observing our result or more extreme if null is true
- **Confidence Interval**: Range of parameter values that could realistically produce our sample
- **Types of Errors**:
  - Type 1 error: Rejecting a true null hypothesis
  - Type 2 error: Failing to reject a false null hypothesis
- **Significance Level**: Tolerable probability for Type 1 error
- **Power**: Ability to detect an effect when it exists (opposite of Type 2 error)

## Types of Statistical Tests
- **One-sample tests**: Characterize a population
- **Two-sample tests**: Compare two groups
- **ANOVA**: Compare three or more groups
- **Chi-square test**: For categorical data in contingency tables
- **Regression**:
  - Linear regression: Relationship between variables
  - Generalized linear models: For binary/count outcomes
  - Maximum likelihood estimation: Method to estimate parameters

## Advanced Topics
- **Longitudinal modeling**: For data collected over time (GEE, mixed effects models)
- **Variable selection**: Choosing predictors to include in models
- **Experimental design**: Randomized controlled trials vs observational studies
- **Causality vs correlation**: Experimental design determines which conclusions can be drawn
- **Types of statistical approaches**:
  - Parametric statistics: Make assumptions about distributions
  - Non-parametric statistics: Fewer assumptions about distributions
  - Semi-parametric statistics: Mix of parametric and non-parametric approaches
- **Prediction**: Using models to predict future observations
- **Machine learning**: Often uses "black box" models for prediction
- **High-dimensional statistics**: When predictors outnumber observations
- **Causal inference**: Making causal statements from observational data
- **Robust statistics**: Models that work even when assumptions are violated

## Statistical Practice
- Statistical programming languages (R recommended for statistical analysis)
- Exploratory data analysis
- Simulation studies