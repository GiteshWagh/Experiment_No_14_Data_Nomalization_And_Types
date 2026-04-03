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

**Formula:**

\[
X' = \frac{X - X_{min}}{X_{max} - X_{min}}
\]

Where:  
- \(X\) = Original value  
- \(X_{min}\) = Minimum value in dataset  
- \(X_{max}\) = Maximum value in dataset  
- \(X'\) = Normalized value  

---

#### 2. Z-Score Normalization (Standardization)

This technique standardizes data based on mean and standard deviation.

**Formula:**

\[
Z = \frac{X - \mu}{\sigma}
\]

Where:  
- \(X\) = Original value  
- \(\mu\) = Mean of dataset  
- \(\sigma\) = Standard deviation  
- \(Z\) = Standardized value  

---

#### 3. Decimal Scaling Normalization

In this method, values are scaled by dividing by a power of 10.

**Formula:**

\[
X' = \frac{X}{10^j}
\]

Where:  
- \(X\) = Original value  
- \(j\) = Number of digits in the maximum absolute value  
- \(X'\) = Normalized value  

---

### 4.4 Data Types

#### 1. Numerical Data
- Represents measurable quantities  
- Can be continuous (e.g., weight, price) or discrete (e.g., number of items)

#### 2. Categorical Data
- Represents labels or categories  
- Cannot be directly used in mathematical models  

---

### 4.5 Encoding of Categorical Data

Since machine learning models require numerical input, categorical data must be converted into numbers.

---

#### 1. Label Encoding

- Assigns a unique number to each category  
- Example: Male → 0, Female → 1  

#### Advantages:
- Simple and memory efficient  

#### Limitation:
- May introduce unintended order among categories  

---

#### 2. One-Hot Encoding

- Creates separate columns for each category  
- Each category is represented by binary values (0 or 1)

#### Advantages:
- No ordinal relationship between categories  
- More accurate representation  

---

#### 3. Dummy Encoding

- Similar to one-hot encoding  
- Removes one column to avoid redundancy  

#### Advantages:
- Prevents multicollinearity  
- Reduces dimensionality  

---

### 4.6 Application on Dataset

In this experiment, normalization techniques were applied to datasets such as fruit data and product datasets. Features like price, calories, ratings, and units sold were normalized using different methods.

Categorical variables such as gender, payment method, product category, and city were converted into numerical form using encoding techniques. This transformation made the data suitable for further analysis and modeling.

---

### 4.7 Importance of Normalization and Encoding

- Makes data suitable for machine learning models  
- Improves accuracy and efficiency  
- Ensures consistency in data representation  
- Helps in handling both numerical and categorical data effectively  

---

## 5. Conclusion

In this experiment, various data normalization techniques such as Min-Max normalization, Z-score normalization, and decimal scaling were successfully studied and applied. These techniques helped in scaling data to a uniform range, improving analysis accuracy.

Additionally, categorical data was converted into numerical form using label encoding, one-hot encoding, and dummy encoding. This transformation is essential for using data in machine learning models.

Overall, this experiment demonstrated the importance of normalization and data type handling in exploratory data analysis and highlighted how Python provides efficient tools for preparing high-quality datasets.

---
