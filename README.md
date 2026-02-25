📊 Basic Statistics – Assignment 2  
 99% Confidence Interval Estimation

 📌 Project Overview
This assignment focuses on constructing 99% confidence intervals for the mean durability of print-heads using statistical techniques.

The objective is to understand the difference between:
- Confidence Interval using Sample Standard Deviation (t-distribution)
- Confidence Interval using Known Population Standard Deviation (z-distribution)

---

 📂 Problem Statement

A manufacturer tested 15 print-heads and recorded their durability (in millions of characters).  
Using the given sample data, we were required to:

1. Construct a 99% Confidence Interval using the sample standard deviation.
2. Construct a 99% Confidence Interval assuming population standard deviation is known (σ = 0.2).

---

 🧠 Statistical Approach

 🔹 Case 1 – Using Sample Standard Deviation
- Population standard deviation unknown
- Sample size < 30
- Used **t-distribution**
- Degrees of freedom = n - 1

Formula:

CI = x̄ ± t(α/2, n-1) × (s / √n)

---

 🔹 Case 2 – Using Known Population Standard Deviation
- Population standard deviation known
- Used **Z-distribution**

Formula:

CI = x̄ ± Z(α/2) × (σ / √n)

---

 📊 Results

Using t-distribution:
99% Confidence Interval ≈ (1.090 , 1.387)

 Using Z-distribution:
99% Confidence Interval ≈ (1.106 , 1.372)

---

 📈 Interpretation

We are 99% confident that the true mean durability of the print-heads lies within the calculated confidence interval.

The interval using the t-distribution is slightly wider due to additional uncertainty from estimating the population standard deviation.

---

 🛠 Tools Used
- Python
- NumPy
- SciPy
- Google Colab

---

 👨‍💻 Author
Mahesh Kale  
B.Sc CS (AIML & VR)  
Data Science – Batch May 2025
