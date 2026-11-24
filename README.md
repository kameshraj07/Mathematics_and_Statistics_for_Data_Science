# 📊 Mathematical & Statistical Analysis for Data Science

## 📌 Project Overview

This project demonstrates the practical implementation of mathematical and statistical concepts used in Data Science using Python.

The project covers three major areas:

1. Linear Algebra Implementation
2. Probability Concepts
3. Descriptive Statistics

The objective is to understand mathematical operations, probability concepts, probability distributions, and descriptive statistical measures using Python libraries such as NumPy, Pandas, and the Python Statistics module.

## 🎯 Project Objectives

- Perform vector and matrix operations using NumPy.
- Calculate matrix determinants and inverses.
- Compute eigenvalues and eigenvectors.
- Apply probability concepts to real-world sales scenarios.
- Calculate the probability of successful sales across customer segments.
- Apply Bayes' Theorem.
- Simulate binomial distributions.
- Generate normal and uniform distributions.
- Calculate descriptive statistical measures.
- Interpret skewness and kurtosis of sales data.

## 🛠️ Technologies Used

- **Python 3** – Programming language
- **NumPy** – Numerical and mathematical computations
- **Pandas** – Data manipulation and statistical analysis
- **Statistics** – Statistical calculations using Python's standard library
- **Google Colab / Jupyter Notebook** – Development environment

## 📂 Project Structure

```text
Mathematical-Statistical-Analysis/
│
├── Mathematical_&_Statistical_Analysis_for_Data_Science.ipynb
│
├── README.md
│
└── requirements.txt
```

## 🔄 Tasks Covered

### Task 1 – Linear Algebra Implementation

Implemented fundamental linear algebra operations using NumPy.

**Operations performed:**

- Vector Addition
- Vector Subtraction
- Dot Product
- Matrix Addition
- Matrix Multiplication
- Matrix Determinant
- Matrix Inverse
- Eigenvalues
- Eigenvectors

NumPy arrays and NumPy linear algebra functions were used to perform mathematical computations efficiently.

### Task 2 – Probability Concepts

Applied probability concepts using a practical sales scenario.

**Customer Segments:**

- Premium Customers
- Regular Customers

**Purchase Probabilities:**

| Customer Segment | Purchase Probability |
|---|---:|
| Premium Customers | 80% |
| Regular Customers | 50% |

**Key Result:**

The calculated probability of successful sales is approximately **69.5%**.

#### Bayes' Theorem

Applied Bayes' Theorem to calculate the conditional probability of an event based on new information.

**Calculated Result:**

P(A|B) ≈ 0.5161

The probability is approximately **51.61%**.

#### Binomial Distribution

Simulated a binomial distribution using the following parameters:

| Parameter | Value |
|---|---:|
| Number of Trials | 20 |
| Success Probability | 0.65 |
| Number of Simulations | 20 |

#### Normal and Uniform Distributions

Generated two probability distributions using NumPy:

**Normal Distribution:**
- Mean = 50
- Standard Deviation = 10
- Observations = 1,000

**Uniform Distribution:**
- Minimum = 0
- Maximum = 1
- Observations = 1,000

### Task 3 – Descriptive Statistics

Performed descriptive statistical analysis on a sales dataset containing 20 observations.

The following statistical measures were calculated:

| Statistical Measure | Result |
|---|---:|
| Mean | 165.50 |
| Median | 165.00 |
| Mode | 135, 145, 155, 165, 175 |
| Range | 90 |
| Population Variance | 534.75 |
| Population Standard Deviation | 23.1247 |
| Skewness | 0.0326 |
| Excess Kurtosis | -0.5493 |

#### Statistical Interpretation

- **Mean:** The average sales value is 165.50.
- **Median:** The middle sales value is 165.00.
- **Mode:** Five values occur most frequently: 135, 145, 155, 165, and 175.
- **Range:** The difference between maximum and minimum sales is 90.
- **Variance:** Measures the spread of sales values around the mean.
- **Standard Deviation:** Indicates how much sales values typically vary from the mean.
- **Skewness:** The value of 0.0326 indicates a very slight positive skew, making the distribution approximately symmetric.
- **Kurtosis:** The negative value of -0.5493 indicates a flatter distribution with lighter tails compared with a normal distribution.

The mean and median are very close, further supporting the approximately symmetric nature of the dataset.

## 📈 Key Learning Outcomes

Through this project, I gained practical experience in:

- Numerical Computation using NumPy
- Vector and Matrix Operations
- Linear Algebra
- Probability Calculations
- Conditional Probability
- Bayes' Theorem
- Binomial Distribution
- Normal Distribution
- Uniform Distribution
- Descriptive Statistics
- Statistical Interpretation
- Python-Based Data Analysis

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <your-github-repository-link>
```

### 2. Navigate to the Project Directory

```bash
cd Mathematical-Statistical-Analysis
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
numpy
pandas
```

**Note:** The `statistics` module is included in Python's standard library and does not require separate installation.

## ▶️ How to Run the Project

1. Clone or download the repository.
2. Install the required Python libraries.
3. Open the project using Jupyter Notebook, JupyterLab, Visual Studio Code, or Google Colab.
4. Open `M3_Mathematical_&_Statistical_Analysis_for_Data_Science.ipynb`.
5. Execute all notebook cells sequentially.
6. Review the calculations, outputs, and statistical interpretations.

## 📌 Project Status

**Completed** ✅

This project was developed as part of my Data Science learning journey to strengthen my understanding of mathematical and statistical concepts required for Data Analysis and Machine Learning.

## 👨‍💻 Author

**A Kameshraj**

Aspiring Data Scientist

