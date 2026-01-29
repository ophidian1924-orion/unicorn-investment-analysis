# Unicorn Investment Screening Dashboard

## Business Problem
The management team aims to identify high-potential unicorn companies for strategic investment.  
Given limited capital and increasing investor crowding, the goal is to prioritize unicorns that:
- Have fewer existing investors
- Achieved unicorn status rapidly
- Are not in exit stages (IPO, acquired, divested)

## Objective
Develop a data-driven screening model and interactive dashboard to rank unicorn companies based on investment attractiveness.

## Dataset
The dataset contains 1,037 unicorn companies with attributes including:
- Valuation (USD billions)
- Founding year and date joined unicorn list
- Industry and geography
- Investor count and funding raised
- Financial stage and exits

## Methodology
1. Data cleaning and preprocessing using Python
2. Feature engineering:
   - Time to Unicorn
   - Investment eligibility flag
3. Normalization and weighted investment scoring
4. Interactive dashboard development using Tableau

## Key Metrics
- Time to Unicorn (years)
- Number of investors
- Composite Investment Score

## Dashboard
The Tableau dashboard enables:
- Filtering by industry, geography, and valuation
- Identification of top investment candidates
- Visual analysis of growth velocity and investor saturation

🔗 **Tableau Public Dashboard:** *(add link here)*

## 📁 Repository Structure
unicorn-investment-analysis/
│
├── data/
├── notebooks/
├── tableau/
├── README.md


## Business Insights
The analysis highlights companies with rapid scaling and low investor saturation, primarily concentrated in technology-driven sectors across major startup hubs.

## Tools Used
- Python (Pandas, NumPy)
- Tableau Public
- GitHub
