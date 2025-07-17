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
| ![X³ Plot](images/x_cubed_plot.png) | ![X² Plot](images/x_squared_plot.png) |

> 💡 Replace `images/x_cubed_plot.png` and `x_squared_plot.png` with your actual plot image files.

---

## ⚙️ How to Run

### 🔧 Prerequisites
Install required libraries:

```bash
pip install numpy pandas matplotlib scipy
