# Macro Terminal V4: Systematic Quant Engine

A professional-grade macro factor model and cross-asset allocation simulator. This terminal moves beyond simple "rule-based" dashboards into a **continuous quantitative inference engine**.

![Version](https://img.shields.io/badge/Version-4.0_Quant_Engine-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🧠 Core Methodology

Macro Terminal V4 utilizes a **Non-Linear Factor Matrix** to transform raw economic data into systematic portfolio weights. Unlike traditional simulators, this project addresses the complex interdependencies of macro variables.

### Key Quantitative Features:
- **Z-Score Engine:** Standardizes GDP, Inflation, and Liquidity gaps to ensure dimensional consistency across the model.
- **Softmax Optimization:** Implements a Softmax layer for asset allocation, providing a continuous, convex transition between assets instead of rigid "if-else" switching.
- **Interaction Effects:** Models non-linear "cross-factor" terms (e.g., Growth × Inflation) to detect regime-specific anomalies like Stagflation.
- **Soft Regime Classification:** Uses probabilistic dominance to classify the macro environment into Expansion, Overheating, Stagflation, or Recession.

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3 (Custom Grid Architecture)
- **Visualization:** [Chart.js](https://www.chartjs.org/) for real-time factor expectancy and bond convexity surfaces.
- **Logic:** Vanilla JavaScript (ES6+) implementing a systematic quant pipeline.

## 📈 The Pipeline
1. **Standardization:** Raw inputs (r, π, g, r*) → Standard Deviations (Z).
2. **Expectancy Projection:** $R_i = \alpha + \sum(\beta_j Z_j) + \text{Interactions}$.
3. **Weight Optimization:** Weights normalized via Softmax function for optimal factor loading.
4. **Causal Narrative:** Generates a real-time linguistic summary of the model's inference.

## Live Demo : [Click Here]()

---
**Developed by [Amaanullah Bhatti](https://github.com/amaanullah21)**
