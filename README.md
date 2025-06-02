# Urban Multifamily Asset Management Case Study

**Created by Jackie First**  
**Email:** jackiefirst6@gmail.com.com  
**LinkedIn:** www.linkedin.com/in/jackie-first 

**Disclaimer:** All data used in this repository is **simulated** for demonstration purposes. No real client or proprietary information is included.  

This case study showcases a complete, end-to-end analysis of acquiring and managing a 16-unit multifamily property. It illustrates household budgeting, underwriting, quarterly performance tracking, scenario analysis, and investor-ready deliverables.  

---

## 🚀 How to Navigate This Repository

1. **Underwrite the Deal**  
   - Open `/models/acquisition_underwriting_model.xlsx`  
   - Review the “Assumptions” tab for purchase, financing, rent, vacancy, and expense inputs.  
   - Check the “Cash Flow” tab for Year 1–10 projections, and “Returns” for IRR & Equity Multiple.  

2. **Track Quarterly Performance**  
   - In `/models/asset_management_dashboard.xlsx`, open “Actual vs Pro Forma” to see Q1–Q4 simulated results.  
   - Go to the “Dashboard” sheet to view visual comparisons of EGI, NOI, Cash Flow, DSCR, and Occupancy.  

3. **Analyze Exit Scenarios**  
   - Open `/models/scenario_analysis_model.xlsx`.  
   - Compare Base Case (hold 10 years), Refinance at Year 5, and CapEx + Sale at Year 7.  
   - Review each sheet’s summary IRR and Equity Multiple to understand tradeoffs.  

4. **Review Investor Materials**  
   - `/writeups/investment_memo.pdf`: Learn how to structure a professional deal overview.  
   - `/writeups/quarterly_asset_update_Q4.pdf`: See how to communicate quarterly results and variances.  
   - `/writeups/exit_strategy_decision_memo.pdf`: Examine a concise recommendation memo comparing exit options.  

5. **Inspect Supporting Data & Visuals**  
   - `/data/rent_comparables.csv`: Check how rent comps inform rent assumptions.  
   - `/data/property_assumptions.json`: See how inputs are structured for modeling.  
   - `/visuals/`: Browse charts that highlight key metrics (IRR graph, dashboard screenshots, cash flow charts).  

---


### 1. `/models/`  
- **`acquisition_underwriting_model.xlsx`**  
  - Contains a 10-year pro forma model with separate sheets for assumptions, year-by-year cash flows, and return metrics (IRR, equity multiple).  
  - Illustrates how to underwrite a hypothetical 16-unit building (rent assumptions, expense ratios, financing).  

- **`asset_management_dashboard.xlsx`**  
  - Includes one sheet (“Actual vs Pro Forma”) showing four quarters of simulated actual performance versus the original budget.  
  - The “Dashboard” sheet features five charts (EGI vs Pro Forma, NOI vs Pro Forma, Cash Flow vs Pro Forma, DSCR vs Pro Forma, and Occupancy trends).  
  - Demonstrates quarterly variance analysis and key metric tracking.  

- **`scenario_analysis_model.xlsx`**  
  - Three tabs model different exit strategies:  
    1. **Base Case (10-Year Hold)**  
    2. **Refinance at Year 5, Hold to Year 10**  
    3. **CapEx + Sale at Year 7**  
  - Each tab shows year-by-year cash flows and summary IRR/Equity Multiple.  
  - Highlights ability to stress-test deals and recommend optimal strategy.  

---

### 2. `/writeups/`  
- **`investment_memo.pdf`**  
  - A concise 1–2 page summary of the deal: property overview, market rationale, financial highlights, risks, and next steps.  
  - Example of an investor-ready “teaser” you’d send to a potential equity partner or lender.  

- **`quarterly_asset_update_Q4.pdf`**  
  - A year-end (Q1–Q4) performance report comparing actuals to pro forma.  
  - Includes tables of revenue vs budget, NOI variances, DSCR, occupancy metrics, and operational commentary.  
  - Demonstrates how to communicate accurately and transparently to stakeholders.  

- **`exit_strategy_decision_memo.pdf`**  
  - A 1–2 page memo evaluating three exit paths (10-year hold, refinance at Year 5, or CapEx + sale at Year 7).  
  - Compares IRR, equity multiple, liquidity timing, and risk, then recommends a course of action.  
  - Shows strategic thinking and ability to guide investors in decision-making.  

---

### 3. `/data/`  
- **`rent_comparables.csv`**  
  - Simulated rent‐comps (address, unit type, square footage, monthly rent, date).  
  - Demonstrates data gathering and rent-comparable analysis.  

- **`property_assumptions.json`**  
  - Structured JSON file storing all key inputs for the acquisition model (purchase price, financing terms, rent, expense ratios, rent growth, vacancy).  
  - Illustrates proficiency in organizing inputs for reproducible modeling.  

---

### 4. `/visuals/`  
Contains exported images of key charts:  
- **`irr_graph.png`** – IRR vs. hold period from scenario analysis.  
- **`dashboard_screenshot.png`** – Screenshot of the five-chart dashboard.  
- **`cashflow_comparison_chart.png`** – Visual comparing annual or quarterly cash flows (Pro Forma vs. Actual).  

---

## 📦 Next Steps / How to Use

1. **Clone or Download the Repository**  
   ```bash
   git clone https://github.com/yourusername/multifamily-asset-management-case.git
   cd multifamily-asset-management-case
