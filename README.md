# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of the Titanic dataset, one of the most well-known datasets in data science and machine learning. The goal of this analysis is to explore passenger demographics, travel characteristics, and survival patterns to gain insights into the factors that influenced survival during the Titanic disaster.

The analysis focuses on understanding the dataset through statistical summaries, visualizations, and data exploration techniques without building predictive models.

---

## Dataset Description

The dataset contains information about passengers aboard the RMS Titanic, including:

* Passenger ID
* Survival status
* Passenger class
* Name
* Gender
* Age
* Number of siblings/spouses aboard
* Number of parents/children aboard
* Ticket number
* Fare paid
* Cabin information
* Port of embarkation

### Target Variable

**Survived**

* 0 = Did Not Survive
* 1 = Survived

---

## Project Objectives

* Understand the structure and characteristics of the dataset.
* Explore the distribution of numerical and categorical variables.
* Analyze survival patterns among different passenger groups.
* Investigate relationships between passenger attributes and survival outcomes.
* Identify meaningful trends and insights through data visualization.

---

## Analysis Workflow

### 1. Data Loading and Inspection

* Loading the dataset
* Exploring dataset dimensions
* Examining data types
* Reviewing summary statistics

### 2. Univariate Analysis

Analysis of individual variables:

* Survival distribution
* Gender distribution
* Passenger class distribution
* Age distribution
* Fare distribution
* Embarkation port distribution

### 3. Bivariate Analysis

Exploring relationships between survival and:

* Gender
* Passenger class
* Age
* Fare
* Embarkation port
* Family-related variables

### 4. Multivariate Analysis

* Combined effects of multiple variables on survival
* Survival patterns across passenger groups

### 5. Correlation Analysis

* Relationships among numerical variables
* Correlation heatmap interpretation

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Insights

Some important findings from the analysis include:

* Female passengers had significantly higher survival rates than male passengers.
* First-class passengers were more likely to survive than second- and third-class passengers.
* Passengers who paid higher fares generally had better survival chances.
* Most passengers were young adults.
* The fare distribution was highly right-skewed, with a small number of passengers paying exceptionally high fares.
* Survival was influenced by a combination of socioeconomic status, gender, and passenger class.


---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/titanic-eda.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the Jupyter Notebook and execute the cells sequentially:

```bash
jupyter notebook
```

---

## Future Improvements

* Feature engineering and preprocessing.
* Predictive modeling using machine learning algorithms.
* Interactive dashboards using Plotly or Tableau.
* Survival prediction comparison across multiple models.

---

## License

This project is intended for educational and learning purposes.
