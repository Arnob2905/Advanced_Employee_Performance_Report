# 📊 Employee Performance Analysis

> Statistical analysis of employee performance and promotions using Python, Pandas, NumPy, and more.

---

## 📌 Project Overview

This project analyzes an employee dataset (`employee_performance.csv`) containing around **4,000 records**. The goal is to apply **statistics**, **probability**, **data visualization**, and **linear algebra** to extract meaningful insights about employee performance and promotions.

---

## 📁 Dataset Description

| Field | Description |
|---|---|
| `Employee_ID` | Unique ID starting from 1001 |
| `Department` | IT, HR, Finance, Marketing, Sales |
| `Age` | Employee age |
| `Salary` | Monthly salary |
| `Projects_Completed` | Number of completed projects |
| `Working_Hours` | Daily working hours |
| `Performance_Score` | Score from 0 to 100 |
| `Promotion_Status` | Yes / No |

---

## 🎯 Objectives

### 🔹 Step 1: Central Tendency & Dispersion

- **Mean**
  ```
  Mean = Σx / n
  ```

- **Median** — Middle value after sorting

- **Mode** — Most frequent value

- **Variance**
  ```
  Variance = Σ(x - μ)² / n
  ```

- **Standard Deviation**
  ```
  σ = √Variance
  ```

---

### 🔹 Step 2: Probability & Events

- **Probability of Promotion**
  ```
  P(Promotion) = Number of Promoted Employees / Total Employees
  ```

- **Conditional Probability**
  ```
  P(A|B) = P(A ∩ B) / P(B)
  ```
  **Example:**
  ```
  P(Promotion | Performance Score > 80)
  ```

- **Contingency Table** — Department vs Promotion Status

---

### 🔹 Step 3: Distribution & Visualization

- 📊 Histogram with Gaussian Curve
- 📈 **Skewness**
  - Positive Skew → Right tail
  - Negative Skew → Left tail
- 📐 **Kurtosis** — Measures peak/flatness of distribution
- 📉 **Q-Q Plot** — Used to check normal distribution

---

### 🔹 Step 4: Linear Algebra

- Create vectors from employee data

- **Dot Product**
  ```
  A · B = Σ(Aᵢ * Bᵢ)
  ```

- **Magnitude (Norm)**
  ```
  ||A|| = √Σ(Aᵢ²)
  ```

- **Angle Between Vectors**
  ```
  cosθ = (A · B) / (||A|| ||B||)
  ```

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

---

## 📊 Key Insights

- ✅ High Performance Score (> 80) increases promotion chances
- ✅ Employees completing more projects are more likely to be promoted
- ✅ Salary distribution is right-skewed
- ✅ More working hours correlate with better performance
- ✅ Sales and Finance departments show higher productivity

---

## ▶️ How to Run

**1. Clone the repository**
```bash
git clone https://github.com/your-username/employee-performance-analysis.git
cd employee-performance-analysis
```

**2. Install required libraries**
```bash
pip install pandas numpy matplotlib seaborn scipy
```

**3. Run the analysis**
```bash
python analysis.py
```

> ⚠️ Make sure `employee_performance.csv` is in the same folder as `analysis.py`.

---

## 📌 Deliverables

- [x] Python Script / Jupyter Notebook
- [x] PDF Report (Theory + Outputs + Insights)

---

## 📂 Project Structure

```
employee-performance-analysis/
│
├── employee_performance.csv    # Dataset
├── analysis.py                 # Main analysis script
├── report.pdf                  # Final PDF report
└── README.md                   # Project documentation
```

---

## 👨‍💻 Author

**Arnob Maity**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

