# Creole Kitchen Co. - AI Operations Case Study

**How Multi-Agent AI Could Save a 3-Unit Restaurant $83K-179K Annually**

[![View Case Study PDF](https://img.shields.io/badge/Download-Case%20Study%20PDF-blue)](Multi-Agent_AI_Restaurant_Operations_Case_Study.pdf)
[![View Notebook](https://img.shields.io/badge/Open-Sentiment%20Analysis-orange)](https://colab.research.google.com/drive/1jdUWoEEXTrXhDLwUU-bAVCojMTrF6k0K?usp=sharing)

---

## 🎯 Executive Summary

This case study demonstrates how a multi-agent AI system can identify and resolve operational inefficiencies in a restaurant business through integrated analysis of POS transactions, customer reviews, inventory data, and labor patterns.

**The Business:**
- Creole Kitchen Co. (fictional case study)
- 3 locations in Greater New Orleans area
- $5M+ annual revenue
- Full-service and fast-casual formats

**The Challenge:**
Analysis of 6 months of operational data (90,000+ POS transactions, 500 customer reviews) revealed 4 critical issues costing an estimated $150K+ annually:

1. **Revenue Concentration Risk:** 55% of revenue from single location
2. **Labor Inefficiency:** Peak volume 9.4x low periods = $44K-62K annual waste
3. **Revenue-Satisfaction Gap:** Top revenue items showing 19%+ negative review rates
4. **Location Performance:** $2.3M annual revenue gap between underperforming units

**The Solution:**
A coordinated system of 5 AI agents monitoring operational data streams in real-time:

- **Customer Insight Agent:** Real-time sentiment analysis, complaint detection
- **Inventory Intelligence Agent:** Cost variance alerts, margin optimization  
- **Labor Optimization Agent:** Demand forecasting, dynamic scheduling
- **Waste Reduction Agent:** Prep-to-sale monitoring, spoilage prevention
- **Executive Synthesis Agent:** Cross-functional insights, strategic reporting

**Projected Impact:**
- Annual value: **$83K - $179K**
- ROI: **94% - 358%**
- Payback period: **2.5 - 7 months**

📄 **[Download Full One-Page Summary (PDF)](link-to-your-pdf)**

---

## 🤖 AI Demonstration: Sentiment Analysis with Hugging Face

I processed 500 customer reviews using `distilbert-base-uncased-finetuned-sst-2-english` to demonstrate AI-powered customer insight analysis.

**Key Findings:**
- **92% agreement** with human-labeled sentiment
- **Identified critical insight:** Crawfish Etouffee (#1 revenue item at $276K) had 19.2% negative sentiment vs. 7.7% for Gumbo Bowl
- **Root cause analysis:** AI correlation revealed supplier cost increase → quality substitution → customer dissatisfaction

**[📊 View Interactive Sentiment Analysis Notebook](link-to-your-colab)**

### Sample Visualizations

[Insert your 3 charts here as images in the README]

---

## 📊 Datasets

All datasets are synthetic but reflect realistic operational patterns based on 20 years of restaurant operations experience.

### POS Transaction Data
- **File:** `creole_kitchen_pos_sample_10pct.csv` (10% sample, full dataset available upon request)
- **Records:** 31,970 line items (10% of 319,705 total)
- **Period:** July - December 2025 (6 months)
- **Revenue:** $2.58M analyzed (annualized)

### Customer Reviews
- **File:** `creole_kitchen_reviews_sample_20pct.csv` (20% sample)
- **Records:** 100 reviews (20% of 500 total)
- **Sources:** Google/Yelp-style reviews (synthetic)
- **Sentiment:** 60% positive, 25% mixed, 15% negative

### Key Insights from Analysis

**Revenue Performance:**
- French Quarter: 55.4% of revenue (concentration risk)
- Garden District: 23.1% of revenue
- Metairie: 21.5% of revenue

**Customer Satisfaction:**
- Overall: 4.1/5.0 average rating
- Best item: Gumbo Bowl (4.27/5.0)
- Needs attention: Crawfish Etouffee (3.97/5.0 with 19.2% negative rate)

**Operational Challenges Quantified:**
- Labor inefficiency: $44K-62K annual waste
- Margin leakage: $74K-148K annually (portion inconsistency)
- Waste: 1.26% of sales (target: <1.0%)

---

## 🛠️ Technical Implementation

**Technologies Used:**
- **Data Generation:** Python, Pandas, NumPy
- **Sentiment Analysis:** Hugging Face Transformers (`distilbert-base-uncased-finetuned-sst-2-english`)
- **Visualization:** Matplotlib, Seaborn
- **Platform:** Google Colab
- **Data Storage:** CSV (portable, accessible)

**Analysis Notebooks:**
1. POS Data Generation & Analysis
2. Customer Reviews Generation
3. Sentiment Analysis (Hugging Face Demo)
4. Operational Insights & ROI Modeling

---

## 📈 Project Structure
```
creole-kitchen-ai-operations-case-study/
├── README.md
├── Case_Study_One_Pager.pdf
├── datasets/
│   ├── creole_kitchen_pos_sample_10pct.csv
│   ├── creole_kitchen_reviews_sample_20pct.csv
│   └── dataset_summary.csv
├── notebooks/
│   ├── Sentiment_Analysis_Demo.ipynb
│   └── (Additional analysis notebooks)
└── visualizations/
    ├── sentiment_analysis_results.png
    ├── sentiment_by_location.png
    ├── menu_item_sentiment.png
    ├── menu_engineering_matrix.png
    └── hourly_patterns_by_location.png
```

---

## 💡 Key Learnings

### Cross-Data Correlation
Integrating POS transaction data with customer sentiment revealed insights invisible to single-source analysis:

- Quality complaints on Crawfish Etouffee coincided with supplier cost increase (ingredient substitution detected in POS margin data)
- Service speed complaints correlated with peak hour understaffing (identified in labor analysis)
- Waste patterns aligned with customer portion inconsistency complaints

**Lesson:** Multi-source data integration provides root cause clarity that single dashboards cannot.

### AI Model Performance
- **Sentiment accuracy:** 92% agreement with human labels
- **Processing speed:** 500 reviews analyzed in ~3 minutes
- **Insight quality:** Identified operational issues human review would have missed or delayed

---

## 🎓 About This Project

This case study demonstrates operational AI architecture design for hospitality and service industries. It showcases:

1. **Operational domain expertise** (20 years restaurant operations)
2. **AI/ML implementation skills** (Hugging Face, Python, data analysis)
3. **Business value focus** (ROI-driven, practical solutions)
4. **End-to-end thinking** (problem identification → solution design → impact quantification)

**Use Cases Beyond Restaurants:**
- Retail (multi-unit stores, inventory optimization)
- Healthcare (patient flow, resource allocation)  
- Field services (scheduling, demand forecasting)
- Hospitality (hotels, event venues)

---

## 📬 Contact

**Lionel Sylvester**  
AI Operations Intelligence Analyst | 20 Years Operations Experience

Specializing in turning operational chaos into AI-orchestrated systems for hospitality, retail, and service businesses.

- **LinkedIn:** [linkedin.com/in/lionel-sly-662658227](https://linkedin.com/in/lionel-sly-662658227)
- **Email:** slylonnie1@gmail.com
- **Portfolio:** This repository

**Interested in AI operations consulting?** I offer free operational assessments for multi-unit businesses. DM me on LinkedIn.

---

## 📄 License

This project is open source for educational and portfolio purposes. Datasets are synthetic. Methodology and analysis frameworks available for discussion.

---

*Last updated: January 2026*
