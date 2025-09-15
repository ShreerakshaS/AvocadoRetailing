# Avocado Retailing Project – Prescriptive Analytics with USDA Data

## Project Overview
This project analyzed the U.S. avocado retail market with a **primary focus on prescriptive analytics**.  
Descriptive and predictive analyses (done briefly) explored seasonal demand patterns and forecasted avocado sales, while the **prescriptive model** delivered actionable strategies for supply chain optimization.

## Data Sources
- **Prescriptive Analysis**: [USDA Market News Portal](https://www.marketnews.usda.gov/mnp/fv-report-retail?portal=fv&locChoose=&commodity=AVOCADOS) – a **government-verified real dataset**, ensuring credibility and real-world applicability.  
- Supplementary data for descriptive/predictive analysis was taken from Kaggle avocado datasets.

## Prescriptive Analytics (Main Contribution)
- **Objective**: Minimize total supply costs while meeting regional avocado demand.  
- **Approach**: Linear Programming optimization model in Python (PuLP).  
- **Decision Variables**: Proportions of **domestic vs. imported avocado supply** allocated to U.S. regions.  
- **Constraints**:
  - Regional demand must be met.  
  - Maintain realistic supply ratios (e.g., ≥ 90% imported, ≤ 10% domestic in most cases).  

### Key Results
- The U.S. avocado market heavily favors **imports (~87%)**, due to cost advantages.  
- Domestic supply is **only competitive in the Midwest region**, where a 10% domestic allocation was feasible.  
- Northeast & Southeast rely **100% on imports**, showing limited viability for domestic producers.  
- Overall, the model shows imports dominate unless domestic costs are significantly reduced.  

### Business Implications
- Retailers and distributors should **strengthen import partnerships** while cautiously boosting local production in competitive regions like the Midwest.  
- Policies to support domestic growers must focus on **cost reduction strategies**.  
- Supply chain risks (e.g., geopolitical trade issues) can be mitigated by **diversifying import sources**.

## Tools & Technologies
- Python (Pandas, NumPy, PuLP, Matplotlib/Seaborn)
- USDA Government Dataset
- Jupyter Notebook
