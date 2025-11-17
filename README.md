# 🦠 COVID-19 Data Analysis Using Python

This repository contains a complete exploratory data analysis (EDA) of COVID-19 data using Python.  
The project focuses on data cleaning, statistical exploration, and visualization of COVID-19 cases across different regions.

---

## 📌 Introduction

The COVID-19 pandemic generated a massive amount of global health data.  
This project analyzes a structured dataset (till **29 April 2020**) to understand the distribution of:

- Confirmed cases  
- Deaths  
- Recoveries  
- Region-wise comparisons  

The analysis also highlights data-quality issues such as missing values and inconsistencies.

---

## 📁 Dataset Description

- **Project Name:** COVID-19 Analysis Project by Chandan  
- **Part of:** Big Data Analysis  
- **Data Source:** Kaggle  
- **Format:** CSV  
- **Total Records:** ~19,000 rows  
- **Columns:** Date, State, Region, Confirmed, Deaths, Recovered  
- **Date Range:** Records updated till **29 April 2020**


---

## 🧹 Data Cleaning & Preprocessing

The dataset contained missing values, especially in the **State** column.  
Preprocessing steps included:

- Checking missing values using `count()` and `isnull().sum()`
- Handling null entries
- Visualizing missing data using a heatmap
- Filtering rows based on conditions (e.g., confirmed > 10)

### 📸 Missing Data Heatmap



![Missing Data Heatmap](https://github.com/chandanm0005/COVID-19-DATA-ANALYSIS/blob/main/Screenshot%202025-11-17%20182632.png?raw=true)

---

## 🧠 Features of the Project

- Loads COVID-19 dataset using Pandas  
- Performs statistical summary using `describe()`  
- Identifies missing values  
- Groups data by regions  
- Applies filtering conditions  
- Sorts values for deeper insights  
- Visualizes data using Matplotlib & Seaborn  

---

## 📝 Problem Statements (Queries Solved)

The following analytical questions were solved during the project:

### **1️⃣ Show the number of Confirmed, Deaths, and Recovered in each Region**

### **2️⃣ Remove all records where the number of Confirmed cases is less than 10**

### **3️⃣ Identify the Region with the maximum number of Confirmed cases**

### **4️⃣ Identify the Region with the minimum number of Death cases**

### **5️⃣ Display the number of Confirmed, Deaths, and Recovered cases reported in India (till 29 April 2020)**

### **6️⃣ Sort the entire dataset with respect to the number of Confirmed cases in ascending order**

### **7️⃣ Sort the entire dataset with respect to the number of Recovered cases in descending order**

---

## 📊 Output & Visual Results

You can include your plots and screenshots here.

### 📌 Region-wise Summary  
![Region Summary](https://github.com/chandanm0005/COVID-19-DATA-ANALYSIS/blob/main/Screenshot%202025-11-17%20183053.png?raw=true)

### 📌 Confirmed Cases Sorted  
`![Confirmed Sorted](images/confirmed_sorted.png)`

### 📌 Recovered Cases Sorted  
`![Recovered Sorted](images/recovered_sorted.png)`

---

## 🛠️ Technologies Used

- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook / VS Code**

---

##📌 Conclusion

This project demonstrates:
- **Effective data cleaning**
- **Exploratory Data Analysis**
- **Region-wise COVID-19 insights**
- **Practical usage of Pandas grouping, sorting, and filtering**
- **Visualization of missing values and case distribution**
- **It serves as a strong foundation for beginners to understand EDA and real-world dataset handling.**



