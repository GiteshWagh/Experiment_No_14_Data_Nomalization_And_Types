# Experiment No. 14: Data Normalization and Data Types

**Name:** Gitesh Wagh  
**PRN:** 25070123163  
**Branch:** F.Y. E&TC (2025–29)  
**Batch:** A1  
**Subject:** Exploratory Data Analysis with Python  

---

## 1. Aim
The aim of this experiment is to study and implement **data normalization techniques** and understand different **data types**, along with converting categorical data into numerical form for effective data analysis.

---

## 2. Objective
- To understand the concept of **data normalization** and its importance.
- To apply different normalization techniques such as **Min-Max, Z-Score, and Decimal Scaling**.
- To understand different **types of data (numerical and categorical)**.
- To convert categorical data into numerical format using encoding techniques.
- To prepare datasets suitable for machine learning and analysis.

---

## 3. Concepts Used

### 3.1 Data Normalization
Data normalization is the process of scaling numerical values into a specific range so that all features contribute equally to analysis.

### 3.2 Types of Normalization
- Min-Max Normalization  
- Z-Score Normalization  
- Decimal Scaling  

### 3.3 Data Types
- Numerical Data (Continuous and Discrete)  
- Categorical Data  

### 3.4 Encoding Techniques
- Label Encoding  
- One-Hot Encoding  
- Dummy Encoding  

---

## 4. Theory

### 4.1 Introduction to Data Normalization

In real-world datasets, values often vary widely in scale. For example, price values may be in thousands, while ratings may be in decimals. Such differences can affect data analysis and machine learning models. Data normalization helps in bringing all values to a common scale without losing their relative differences.

---

### 4.2 Need for Normalization

- Ensures fair comparison between variables  
- Prevents bias due to large values  
- Improves performance of machine learning algorithms  
- Helps in faster convergence during training  

---

### 4.3 Types of Normalization Techniques (With Formulas)

#### 1. Min-Max Normalization

This technique rescales data into a fixed range (usually 0 to 1).

Formula:  
X' = (X - X_min) / (X_max - X_min)

Where:  
- X = Original value  
- X_min = Minimum value  
- X_max = Maximum value  
- X' = Normalized value  

---

#### 2. Z-Score Normalization (Standardization)

This technique standardizes data based on mean and standard deviation.

Formula:  
Z = (X - mean) / standard deviation

Where:  
- X = Original value  
- mean = Average value  
- standard deviation = Spread of data  
- Z = Standardized value  

---

#### 3. Decimal Scaling Normalization

This technique scales values by dividing them by powers of 10.

Formula:  
X' = X / (10^j)

Where:  
- X = Original value  
- j = Number of digits in maximum value  
- X' = Normalized value  

---

### 4.4 Data Types

#### 1. Numerical Data
- Represents measurable quantities  
- Continuous (e.g., weight, price)  
- Discrete (e.g., count)

#### 2. Categorical Data
- Represents labels or categories  
- Cannot be directly used in calculations  

---

### 4.5 Encoding of Categorical Data

#### 1. Label Encoding
- Assigns numbers to categories  
- Example: Male = 0, Female = 1  

#### 2. One-Hot Encoding
- Creates separate columns for each category  
- Uses 0 and 1 values  

#### 3. Dummy Encoding
- Same as one-hot but removes one column  
- Prevents redundancy  

---

### 4.6 Importance of Normalization and Encoding

- Makes data suitable for machine learning  
- Improves accuracy and efficiency  
- Ensures consistency  
- Helps in fair comparison of features  

---

## 5. Conclusion

In this experiment, normalization techniques such as Min-Max, Z-score, and decimal scaling were studied and applied. These methods helped in scaling data effectively.

Categorical data was also converted into numerical form using encoding techniques, making it suitable for analysis and modeling.

Overall, this experiment highlights the importance of data preprocessing in exploratory data analysis and demonstrates how normalization improves data quality and performance.

---
