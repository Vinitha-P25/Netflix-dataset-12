# Netflix Data Analysis

## Project Overview

This project analyzes the Netflix Titles dataset using Python.

The project covers a complete data analysis workflow, including data preprocessing, descriptive statistics, data visualization, probability concepts, and probability distributions.

The main objective is to understand patterns and characteristics of Netflix movies and TV shows through practical data analysis techniques.

---

## Objectives

- Clean and preprocess the Netflix dataset
- Handle missing values and duplicate records
- Perform descriptive statistical analysis
- Create meaningful data visualizations
- Understand basic probability concepts
- Implement conditional probability
- Apply Bayes' theorem
- Understand normal, binomial, and Poisson distributions

---

## Dataset

The Netflix Titles dataset contains information about movies and TV shows available on Netflix.

### Important Columns

- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Git
- GitHub

---

## Data Preprocessing

The following preprocessing steps were implemented:

- Inspected dataset structure and dimensions
- Checked missing values
- Removed duplicate rows
- Filled missing director values
- Filled missing cast values
- Filled missing country values
- Filled missing rating values using the mode
- Forward-filled missing `date_added` values
- Converted `date_added` to datetime format
- Created `year_added` from `date_added`
- Converted movie duration from text into numerical minutes

---

## Descriptive Statistics

Descriptive statistics were applied to numerical variables such as `release_year` and movie duration.

The following concepts were implemented:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Percentiles

The 25th, 50th, and 75th percentiles were calculated to understand the distribution of the data.

---

## Data Visualization

Matplotlib and Seaborn were used to visualize the Netflix dataset.

### Visualizations Included

- Movies vs TV Shows
- Top 10 Countries
- Content Added Per Year
- Ratings Distribution
- Release Year Histogram
- Movie Duration Histogram
- Release Year Box Plot
- Movie Duration Box Plot
- Release Year vs Movie Duration Scatter Plot
- Top 10 Directors
- Top 10 Genres

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

- A Movie
- A TV Show

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

## Project Structure

```text
Netflix-dataset-12/
│
├── README.md
│
└── netflix/
    ├── Netflix_Analysis.ipynb
    ├── netflix_cleaned.csv
    └── netflix_titles(1).csv