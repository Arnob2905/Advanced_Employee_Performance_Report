📊 Employee Performance Analysis Project
📌 Project Overview

This project analyzes an employee dataset (employee_performance.csv) containing around 4000 records.
The goal is to apply statistics, probability, data visualization, and linear algebra to extract meaningful insights about employee performance and promotions.

📁 Dataset Description

The dataset contains the following fields:

Employee_ID – Unique ID starting from 1001
Department – IT, HR, Finance, Marketing, Sales
Age – Employee age
Salary – Monthly salary
Projects_Completed – Number of completed projects
Working_Hours – Daily working hours
Performance_Score – Score from 0 to 100
Promotion_Status – Yes / No
🎯 Objectives
🔹 Step 1: Central Tendency & Dispersion

Mean:

Mean = Σx / n
Median: Middle value after sorting
Mode: Most frequent value

Variance:

Variance = Σ(x - μ)² / n

Standard Deviation:

σ = √Variance
🔹 Step 2: Probability & Events

Probability of Promotion:

P(Promotion) = Number of Promoted Employees / Total Employees

Conditional Probability:

P(A|B) = P(A ∩ B) / P(B)

Example:

P(Promotion | Performance Score > 80)
Contingency Table:
Department vs Promotion Status
🔹 Step 3: Distribution & Visualization
Histogram with Gaussian Curve
Skewness:
Positive Skew → Right tail
Negative Skew → Left tail
Kurtosis:
Measures peak/flatness of distribution
Q-Q Plot:
Used to check normal distribution
🔹 Step 4: Linear Algebra
Create vectors from employee data

Dot Product:

A · B = Σ(Ai * Bi)

Magnitude (Norm):

||A|| = √Σ(Ai²)

Angle Between Vectors:

cosθ = (A · B) / (||A|| ||B||)
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
📊 Key Insights
✅ High Performance Score (>80) increases promotion chances
✅ Employees completing more projects are more likely to be promoted
✅ Salary distribution is right-skewed
✅ More working hours correlate with better performance
✅ Sales and Finance departments show higher productivity
▶️ How to Run

Install required libraries:

pip install pandas numpy matplotlib seaborn scipy

Run the Python file:

python analysis.py

Make sure:

employee_performance.csv

is in the same folder

📌 Deliverables
Python Script / Jupyter Notebook
PDF Report (Theory + Outputs + Insights)
👨‍💻 Author

Arnob Maity
