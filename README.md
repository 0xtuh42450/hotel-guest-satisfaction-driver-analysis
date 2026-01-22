# Hotel Guest Satisfaction Driver Analysis

##  Executive Summary
This project analyzes hotel guest satisfaction survey data to identify which operational service factors most strongly influence overall guest satisfaction — and how those drivers differ between dissatisfied and highly satisfied guests.

By combining interpretable statistical models with machine learning and SHAP explainability, the analysis moves beyond average effects to uncover *why* guests are unhappy, *what* drives recovery, and *which* factors create true guest delight.

---

##  Business Questions
1. Which service attributes most strongly drive overall guest satisfaction?
2. Are satisfaction drivers different for low vs high satisfaction guests?
3. Which factors act as baseline expectations versus delight drivers?

---

##  Methodology
The analysis follows a layered, decision-oriented approach:

- **Exploratory Data Analysis (EDA)**: understand score distributions and data quality
- **Linear Regression**: establish an interpretable baseline for driver impact
- **Random Forest Regression**: capture non-linear relationships and interactions
- **SHAP Explainability**: interpret global drivers and segment-specific effects (low vs high satisfaction guests)

---

##  Key Insights

### 1️⃣ Cleanliness is a baseline requirement
Poor cleanliness strongly decreases satisfaction, while high cleanliness shows diminishing returns. It is necessary to prevent dissatisfaction but does not meaningfully differentiate among highly satisfied guests.

### 2️⃣ Problem resolution drives recovery
For dissatisfied guests, problem resolution is the dominant driver of overall satisfaction, highlighting the importance of service recovery once expectations are breached.

### 3️⃣ Delight is driven by experience
Among highly satisfied guests, staff friendliness and room comfort play a larger role in driving delight and loyalty than hygiene factors.

---

##  Why This Matters
These insights suggest hotel operators should:
- Treat cleanliness as a non-negotiable baseline
- Invest heavily in service recovery processes
- Focus on experiential factors to convert satisfaction into delight

---

##  Tools & Techniques
- Python (pandas, NumPy)
- scikit-learn (Linear Regression, Random Forest)
- SHAP (SHapley Additive exPlanations)
- Jupyter Notebook

---

##  How to Run This Project
1. Clone the repository
2. Open the Jupyter notebook
3. Run all cells (the dataset is included in `/data`)

---

##  Notes
This project uses a synthetic dataset designed to reflect realistic
hotel guest survey behavior for demonstration and portfolio purposes.

---

##  Repository Structure
```text
hotel-guest-satisfaction-driver-analysis/
├── hotel_guest_satisfaction_driver_analysis.ipynb
├── data/
│   └── hotel_survey_synthetic.csv
└── README.md
