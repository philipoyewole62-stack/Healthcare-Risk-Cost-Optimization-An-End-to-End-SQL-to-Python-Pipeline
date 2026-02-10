# 🏥 Healthcare Risk & Cost Exposure Analysis

This project analyzes hospital admissions data to identify **where clinical risk translates into financial exposure**.

Rather than focusing on averages, the analysis uses **Length of Stay (LOS)** as a proxy for hospitalization cost to uncover **risk concentration, volatility, and extreme outcomes** that drive disproportionate healthcare spending.

The project is designed as an end-to-end **SQL → Python** analytics workflow that mirrors how risk and analytics teams investigate cost drivers in real healthcare systems.

---

## Business Problem

Typical patient cases rarely cause healthcare cost overruns.  
They are driven by a **small subset of high-risk admissions** that remain hospitalized far longer than expected.

This project addresses the question:

> **Where does hospitalization risk concentrate, and which clinical signals are associated with extreme cost exposure?**

---

## Key Questions Explored

- How does admission type influence length of stay and cost risk?
- Do abnormal laboratory results correlate with prolonged hospitalization?
- Where do extreme (tail) outcomes occur?
- Which diagnoses and admission categories drive long-stay risk?
- How does clinical risk translate into estimated financial exposure?

---

## Analytical Approach

- Direct querying of hospital data using SQL
- Risk profiling using LOS distributions and percentile thresholds
- Volatility analysis across admission types
- Segmentation of patients by clinical abnormality signals
- Cost exposure estimation using benchmark daily hospitalization costs
- Correlation analysis to identify risk clustering

---

## Repository Structure

healthcare-risk-cost-analysis/
│
├── README.md
├── executive_summary.md
├── data_dictionary.md
├── assumptions_and_limitations.md
├── notebooks/
│   └── healthcare_risk_cost_analysis.ipynb
│
├── visuals/
│   └── risk_correlation_heatmap.png
│
└── requirements.txt

---

## Intended Audience

- Healthcare analytics teams  
- Risk & cost management stakeholders  
- Data analysts working in healthcare, fintech, or operations analytics  

---

## Tools Used

- SQL
- Python (Pandas, NumPy, Matplotlib)
