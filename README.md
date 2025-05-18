# Insurance-Auto-Claims-Analysis

## 📊 Overview

This project focuses on analyzing a dataset of automobile insurance claims filed by customers in the southwestern and western regions of the United States. The analysis was conducted as part of the GBUS 738 course (Fall 2023) to assist an insurance company facing declining profitability.

As a data science consultant, I was tasked with identifying patterns in customer behavior and policy performance to help the company adjust pricing models, refine risk assessment, and boost overall profitability.

---

## 🧩 Business Problem

Auto insurance companies must accurately assess risk and price premiums to remain profitable. Recently, the client company has seen a decline in profitability. The goal of this analysis is to explore key factors contributing to claims costs and identify profitable customer segments, policies, and risk drivers.

---

## 📦 Dataset

The dataset `claims_df` contains **6,249 rows**, each representing a unique insurance claim. It includes variables such as:

- `customer_id`, `state`, `education`, `employment_status`, `gender`
- `monthly_premium`, `policy_type`, `vehicle_class`, `vehicle_size`
- `total_claims`, `total_claims_amount`, `customer_lifetime_value`, etc.

> Source: [claims_df.rds](https://gmubusinessanalytics.netlify.app/data/claims_df.rds)

---

## 🎯 Project Goals

- Identify highly profitable customer segments
- Determine policy types linked to fewer/more claims
- Detect "problem customers" with frequent or costly claims
- Evaluate geographic and demographic trends
- Generate actionable pricing and policy recommendations

---

## 🛠️ Tools & Libraries Used

- **Language**: R
- **Libraries**:
  - `tidyverse` (dplyr, ggplot2, tidyr)
  - `ggplot2` for data visualization
  - `cor()` for correlation analysis

---

## 🔍 Key Findings

- **Corporate policies** showed the highest profitability among all customer types
- **Special policies** had the fewest number of claims but strong profitability
- **California** was the state with the highest number of claims (25% of total)
- **Married customers** filed the most claims
- **Policy tenure** was positively correlated (0.55) with customer lifetime value (CLV)
- **Luxury vehicle owners** did not make more claims than economy car owners
- **Males with Associate degrees** showed highest average profit margins

> Visualizations included: bar charts, heatmaps, histograms, scatter plots.

---

## 🚀 How to Run the Project

1. Clone this repository
2. Open the `Ritesh_analysis_project.ipynb` file (R Markdown or Jupyter w/ R kernel)
3. Ensure internet access to load dataset:
```r
claims_df <- readRDS(url('https://gmubusinessanalytics.netlify.app/data/claims_df.rds'))
```
4. Execute all cells sequentially for reproducible results

---

## 📁 Folder Structure

```
project-root/
│
├── Ritesh_analysis_project.ipynb     # Main analysis notebook
├── README.md                         # Project documentation
├── Data_Analysis_Code_Review.pdf     # Project requirements & rubric
└── images/                           # (Optional) visual assets
```

---

## 👤 Author

**Ritesh**  
Data Science & Business Analytics

---

## 🙌 Acknowledgments

Thanks to [GMU Business Analytics](https://www.gmu.edu/) and the GBUS 738 faculty for providing the dataset and guidance.

---
