# Netflix Data Analysis

## Project Overview

This project analyzes the Netflix Titles dataset using Python.

The project covers a complete data analysis workflow, including data preprocessing, descriptive statistics, data visualization, probability concepts, probability distributions, and inferential statistics.

The main objective is to understand patterns and characteristics of Netflix movies and TV shows through practical data analysis techniques.

---

## Objectives

<<<<<<< HEAD
* Clean and preprocess the Netflix dataset
* Handle missing values and duplicate records
* Perform descriptive statistical analysis
* Create meaningful data visualizations
* Understand basic probability concepts
* Implement conditional probability
* Apply Bayes' theorem
* Understand normal, binomial, and Poisson distributions
* Apply sampling and the Central Limit Theorem
* Perform hypothesis testing
* Analyze covariance and correlation
=======
- Clean and preprocess the Netflix dataset
- Handle missing values and duplicate records
- Perform descriptive statistical analysis
- Create meaningful data visualizations
- Understand basic probability concepts
- Implement conditional probability
- Apply Bayes' theorem
- Understand normal, binomial, and Poisson distributions
- Apply sampling techniques
- Demonstrate the Central Limit Theorem
- Perform hypothesis testing using p-values
- Implement a one-sample t-test
- Implement a chi-square test
- Calculate covariance
- Calculate the correlation coefficient
- Understand correlation vs causation
>>>>>>> a643905 (Updated README with inferential statistics)

---

## Dataset

The Netflix Titles dataset contains information about movies and TV shows available on Netflix.

### Important Columns

* `show_id`
* `type`
* `title`
* `director`
* `cast`
* `country`
* `date_added`
* `release_year`
* `rating`
* `duration`
* `listed_in`
* `description`

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook
* Git
* GitHub

---

## Data Preprocessing

The following preprocessing steps were implemented:

* Inspected dataset structure and dimensions
* Checked missing values
* Removed duplicate rows
* Filled missing director values
* Filled missing cast values
* Filled missing country values
* Filled missing rating values using the mode
* Forward-filled missing `date_added` values
* Converted `date_added` to datetime format
* Created `year_added` from `date_added`
* Converted movie duration from text into numerical minutes

---

## Descriptive Statistics

Descriptive statistics were applied to numerical variables such as `release_year` and movie duration.

The following concepts were implemented:

* Mean
* Median
* Mode
* Variance
* Standard Deviation
* Percentiles

The 25th, 50th, and 75th percentiles were calculated to understand the distribution of the data.

---

## Data Visualization

Matplotlib and Seaborn were used to visualize the Netflix dataset.

### Visualizations Included

* Movies vs TV Shows
* Top 10 Countries
* Content Added Per Year
* Ratings Distribution
* Release Year Histogram
* Movie Duration Histogram
* Release Year Box Plot
* Movie Duration Box Plot
* Release Year vs Movie Duration Scatter Plot
* Top 10 Directors
* Top 10 Genres

### Histogram

Histograms were used to understand the distribution of numerical variables such as release year and movie duration.

### Box Plot

Box plots were used to understand the median, quartiles, spread, and possible outliers.

### Scatter Plot

Scatter plots were used to examine the relationship between release year and movie duration.

---

## Probability Analysis

Basic probability concepts were implemented using the Netflix dataset.

### Events

The probability of randomly selecting:

* A Movie
* A TV Show

was calculated.

### Conditional Probability

Conditional probability was demonstrated using Netflix ratings.

Example:

`P(Movie | TV-MA)`

This represents the probability that a title is a Movie given that its rating is TV-MA.

### Bayes' Theorem

Bayes' theorem was used to calculate the probability of a title being a Movie given its rating information.

---

## Probability Distributions

Three probability distributions were explored.

### Normal Distribution

Movie duration was used as a numerical example to understand the concept of a normal distribution and probability density.

### Binomial Distribution

A random selection of 10 Netflix titles was used as an example.

The number of Movies selected represents the number of successes in a fixed number of trials.

### Poisson Distribution

The number of Netflix titles added per year was used as an example of counting events within a fixed interval.

---
## Inferential Statistics

Inferential statistics were implemented using the Netflix dataset to make statistical conclusions from samples and analyze relationships between variables.

### Sampling

A random sample of Netflix release years was selected and compared with the full population.

### Central Limit Theorem

Repeated random samples were taken from the release-year data and the distribution of sample means was visualized to demonstrate the Central Limit Theorem.

### Hypothesis Testing

Hypothesis testing was used to make statistical decisions using:

- Null hypothesis (H₀)
- Alternative hypothesis (H₁)
- Significance level
- P-value

### One-Sample T-Test

A one-sample t-test was used to test whether the average movie duration is significantly different from 90 minutes.

### Chi-Square Test

A chi-square test was used to investigate whether Netflix content type and rating are statistically associated.

### Covariance

Covariance was calculated between `release_year` and movie duration to understand how the two numerical variables vary together.

### Correlation

The Pearson correlation coefficient was calculated between `release_year` and movie duration to measure the strength and direction of their linear relationship.

### Correlation vs Causation

The project demonstrates that correlation between two variables does not necessarily mean that one variable causes the other.

## Inferential Statistics

Inferential statistics were used to draw conclusions from samples and investigate relationships within the Netflix dataset.

### Sampling

A random sample of Netflix release years was selected from the dataset and compared with the population.

### Central Limit Theorem

Repeated random samples were taken from the Netflix release-year data.

The distribution of the sample means was visualized to demonstrate the Central Limit Theorem.

### Hypothesis Testing

Hypothesis testing was used to make statistical decisions using a null hypothesis, alternative hypothesis, significance level, and p-value.

### One-Sample T-Test

A one-sample t-test was performed to test whether the average movie duration is significantly different from 90 minutes.

* **Null hypothesis (H₀):** Mean movie duration = 90 minutes
* **Alternative hypothesis (H₁):** Mean movie duration ≠ 90 minutes
* **Significance level:** 0.05

### Chi-Square Test

A chi-square test was used to examine whether Netflix content type and rating are statistically associated.

* **Null hypothesis (H₀):** Type and rating are independent.
* **Alternative hypothesis (H₁):** Type and rating are associated.

### Covariance

Covariance was calculated between `release_year` and movie duration to understand how the two numerical variables vary together.

### Correlation

The Pearson correlation coefficient was calculated between `release_year` and movie duration.

The correlation coefficient was used to identify the direction and strength of their linear relationship.

### Correlation vs Causation

The project also demonstrates that correlation does not necessarily imply causation. A statistical relationship between release year and movie duration does not by itself prove that one variable causes the other.

---

## Project Structure

```text
Netflix-dataset-12/
│
├── README.md
├── requirements.txt
│
└── netflix/
    ├── Netflix_Analysis.ipynb
    ├── netflix_cleaned.csv
    └── netflix_titles(1).csv
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Vinitha-P25/Netflix-dataset-12.git
```

### 2. Navigate to the project

```bash
cd Netflix-dataset-12
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Open:

```text
netflix/Netflix_Analysis.ipynb
```

Run the notebook cells from top to bottom.

---

## Key Learning Outcomes

This project provided practical experience with:

* Data cleaning and preprocessing
* Pandas DataFrame operations
* NumPy numerical operations
* Descriptive statistics
* Data visualization
* Probability concepts
* Probability distributions
* Sampling
* Central Limit Theorem
* Hypothesis testing
* T-test
* Chi-square test
* Covariance
* Correlation
* Correlation vs causation
* Jupyter Notebook
* Git and GitHub

---

## Conclusion

This project demonstrates a complete Python-based data analysis workflow using a real-world Netflix dataset.

It combines data preprocessing, descriptive statistics, visualization, probability, probability distributions, and inferential statistics to understand and analyze Netflix content.

---
