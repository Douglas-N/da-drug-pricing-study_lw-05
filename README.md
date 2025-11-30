# Drug Pricing and RWE Dataset Modelling

## Project Overview
This project explores the pricing landscape of high-cost cancer medications using **real-world evidence (RWE)**, including insurance claims, electronic medical records (EMRs), prescription rates, and public reimbursement records.  

The goal is to analyze cost patterns, treatment delays, and prescribing behaviors to generate actionable insights for patients, payers, policymakers, and healthcare providers.

---

## Key Questions
- How do cancer drug prices vary across drug types, indications, or healthcare systems?  
- What delays or barriers affect patient access to high-cost oncology treatment?  
- Which specialties and regions show the highest or lowest prescribing rates for drugs?  
- How does patient access to oncology therapies in Germany compare to other areas?

---

## Data Sources
- **GAmSi** – GKV Arzneimittel-Schnellinformation (German public reimbursement data): [https://www.gkv-gamsi.de](https://www.gkv-gamsi.de)  
- **Lauer-Taxe** – Germany’s drug price database and Health Care Provider information: [https://www.lauer-fischer.de](https://www.lauer-fischer.de)  
- **WHO - Global Cancer Observatory (GCO)** – Cancer incidence and prevalence data: [https://gco.iarc.fr/en](https://gco.iarc.fr/en)  

---

## Deliverables
1. **Interactive Dashboard** – Display price per drug class, region, or year.  
2. **Geospatial Maps** – Visualize prescribing rates across German states or EU countries.  
3. **Trend Charts** – Display the evolution of cancer drug costs over time, alongside comparisons with other historical therapies submitted for repricing.  

---
## repository Structure

│
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for EDA and visualizations
├── src/ # Scripts for data cleaning, analysis, and modeling
├── dashboards/ # Interactive dashboards (Plotly, Dash, or Streamlit)
├── requirements.txt # Python dependencies
├── README.md
└── .gitignore
