# 📈 Correlation Coefficients: Pearson vs Spearman vs Kendall

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()

This project demonstrates the differences between **Pearson**, **Spearman**, and **Kendall** correlation coefficients when applied to:
- A **monotonic non-linear** function: `Y = X³`
- A **non-monotonic** function: `Y = X²`

It highlights how correlation measures behave under different data relationships—particularly where linearity or monotonicity is (or isn’t) present.

---

## 📊 Examples

### ✅ Example 1: Y = X³ (Monotonic Non-linear)
| Metric      | Value     |
|-------------|-----------|
| Pearson     | ≈ 0.96    |
| Spearman    | 1.00      |
| Kendall     | 1.00      |

### ❌ Example 2: Y = X² (Non-monotonic)
| Metric      | Value     |
|-------------|-----------|
| Pearson     | ≈ 0.00    |
| Spearman    | ≈ 0.00    |
| Kendall     | ≈ 0.00    |

---

## 🖼 Visualization

| Monotonic Non-Linear (`Y = X³`) | Non-Monotonic (`Y = X²`) |
|----------------------------------|----------------------------|
| <img width="590" height="390" alt="image" src="https://github.com/user-attachments/assets/df97c682-a362-4574-8b97-1535233afe49" /> | <img width="590" height="390" alt="image" src="https://github.com/user-attachments/assets/9c802d95-c27b-46ff-b38e-a395da554b5c" /> |


---

## ⚙️ How to Run

### 🔧 Prerequisites
Install required libraries:

```bash
pip install numpy pandas matplotlib scipy
