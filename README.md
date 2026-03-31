# 🏛️ Credit Risk & Recovery Strategy Lab

**Author:** gram99  
**Target Stakeholders:** Recovery Operations, 2nd Line Risk Strategy, & Chief Credit Officers (CCO)

---

### 📊 Executive Summary
The **Credit Risk & Recovery Strategy Lab** is a sophisticated repository of financial engineering and predictive modeling tools designed to optimize the **Net Present Value (NPV)** of delinquent portfolios. By bridging the gap between 1st-line operational capacity and 2nd-line risk appetite, this suite provides the quantitative framework necessary to solve the "Hold vs. Liquidate" dilemma and drive institutional **ROTCE**.

#### Strategic Business Value
*   **Capital Efficiency (CET1):** Utilizes PD/LGD/EAD matrices to model inherent loss, directly informing capital buffer requirements and RWA reduction.
*   **Yield Optimization:** Deploys DCF and NPV models to identify the "Crossover Point" where internal recovery efforts outperform external debt sales.
*   **Behavioral Segmentation:** Replaces broad collections with "Propensity to Pay" (PTP) scoring, ensuring high-touch resources are allocated to high-yield targets.

---

### 🚀 Strategic Modules & Decision Engines
The repository is structured into functional "Labs" that mirror the lifecycle of a delinquent account.

#### 🧠 Propensity & Behavioral Segmentation
*   **Goal:** Differentiate "Will-Pay" from "Won't-Pay" borrowers using advanced classification.
*   **Core Assets:** `PTP_Model.ipynb`, `PropPay_LogReg_Model.ipynb`, `Comm_Pref_Segmentation.ipynb`, `KNN_CreditModel.ipynb`
*   **Impact:** Enables precision communication (e.g., SMS vs. Legal) based on historical payment velocity and contact preference.

#### ⚖️ Financial Engineering & Liquidation Strategy
*   **Goal:** Determine the most profitable recovery path through time-value-of-money (TVM) analysis.
*   **Core Assets:** `NPV_Liquidation.ipynb`, `DCF_Model.ipynb`, `Liquidation_Decision_Tool.ipynb`, `Cure_v_Roll_Rate.ipynb`
*   **Impact:** Models the "Yield Premium" of holding accounts vs. the immediate cash-flow benefit of bulk asset sales.

#### 📉 Risk Exposure & Loss Modeling
*   **Goal:** Quantify the "Inherent Loss" within credit card and retail portfolios.
*   **Core Assets:** `EAD_PD_LGD_Matrix.ipynb`, `PD_LGD_Model.ipynb`, `InherentLossCreditCard.ipynb`, `CreditClassification.ipynb`
*   **Impact:** Provides 2nd-line defense with a structured view of Probability of Default (PD) and Loss Given Default (LGD) quadrants.

#### 📍 Visual Analytics & Risk Matrices
*   **Goal:** Provide "At-a-Glance" portfolio health snapshots for risk committees.
*   **Core Assets:** `BubbleRiskDollarsDisplayed.ipynb`, `CCardCollectionMatrixMonths.ipynb`, `BubbleMonthsDelinquent.ipynb`
*   **Impact:** Visualizes risk concentration across delinquency buckets to identify emerging "bubbles" before they impact the bottom line.

---

### 🛠️ Technical Implementation
This lab demonstrates proficiency in full-stack financial data science and automated modeling.


| Layer | Technical Stack |
| :--- | :--- |
| **Data Science** | Pandas, NumPy, Yfinance (Market data integration) |
| **Machine Learning** | Scikit-Learn (Logistic Regression, KNN, Classification) |
| **Financial Logic** | Custom DCF/NPV scripts for recovery yield premiums |
| **Visualization** | Matplotlib, Seaborn (Bubble charts and risk heatmaps) |

---

### 📊 Strategic KPI Glossary
The models within this lab are aligned with 2026 Regulatory Compliance and banking standards:

*   **Cure vs. Roll Rate:** The velocity at which delinquent accounts return to "Current" status versus rolling into deeper delinquency.
*   **EAD (Exposure at Default):** The predicted dollar amount at risk at the moment of default.
*   **Operational Capacity Yield:** A unique metric balancing team bandwidth against expected recovery dollars.
*   **Inherent Loss:** The modeled loss expected within a segment before any recovery actions are taken.

---

### 💻 Installation & Usage
To run these models locally and simulate your own portfolio behaviors:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
