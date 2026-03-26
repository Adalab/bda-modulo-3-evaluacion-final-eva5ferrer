# 👩‍💻 Individual assigment Module 3: Eva Ferrer 
# Airline Loyalty Program Analysis

This project performs a comprehensive analysis of an airline loyalty program, focusing on customer behavior, demographics, and flight activity. The analysis is divided into four distinct phases, ranging from initial data processing to advanced statistical testing and visualization.

## 📋 Project Overview

The main objective is to understand how customer profiles (education, salary, marital status) influence their engagement with the loyalty program (flights booked, points accumulated). This insight helps in optimizing loyalty strategies and tailoring offers to specific customer segments.

## 📁 Project Structure

The project is organized into four sequential phases:

### Phase 1: Data Exploration and Cleaning
- **Initial Exploration:** Identifying missing values, duplicates, and data types.
- **Cleaning:** Handling null values (using Scikit-learn's `KNNImputer` and `IterativeImputer`), normalizing column names, and merging datasets.
- **Output:** Cleaned datasets stored in the `clean-data/` directory.

### Phase 2: Statistical Analysis
- **Descriptive Statistics:** Summarizing key metrics like total flights and loyalty points.
- **Inferential Statistics:** Testing hypotheses about customer behavior across different segments.

### Phase 3: Data Visualization
- **Visual Insights:** Creating charts and graphs (using Seaborn and Matplotlib) to identify trends, correlations, and outliers.
- **Analysis:** Exploring the relationship between demographics and flight activity.

### Phase 4: Flights Booked by Education
- **Specific Analysis:** A targeted study on how educational level impacts the number of flights booked.
- **Statistical Testing:** Applying A/B testing or ANOVA to determine if differences between groups are statistically significant.

## 📊 Data Description

The project uses two primary datasets located in `original-data/`:

1.  **Customer Flight Activity:** Monthly records of flights booked, distances flown, and loyalty points transactions.
2.  **Customer Loyalty History:** Detailed customer profiles including demographics (Gender, Education, Salary), location, and membership details (CLV, Enrollment Date).

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas & NumPy:** Data manipulation and analysis.
- **Matplotlib & Seaborn:** Data visualization.
- **Scikit-learn:** Advanced data imputation techniques.
- **Jupyter Notebooks:** Interactive development environment.

## 📂 Repository Structure

```text
├── clean-data/              # Processed and merged CSV files
├── original-data/           # Raw data files
├── phase-1-data-exploration-cleaning.ipynb
├── phase-2-statistical-analysis.ipynb
├── phase-3-visualization.ipynb
├── phase-4-flights-booked-by-education.ipynb
├── columns-description.md    # Detailed metadata for the datasets
└── README.md                # Project documentation
```

## 🚀 Getting Started

1. Clone the repository.
2. Install the required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`.
3. Run the Jupyter Notebooks in order (Phase 1 to Phase 4).
