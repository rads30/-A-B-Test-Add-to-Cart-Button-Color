
This notebook demonstrates a simple **A/B test** to evaluate the impact of changing the Add-to-Cart button color on conversion rates for an ecommerce site.  
A/B Test: Add-to-Cart Button Color

Author: Radhika Patil  


---

Project Overview

This notebook demonstrates a simple **A/B test** to evaluate the impact of changing the **Add-to-Cart button color** on conversion rates for an ecommerce site.  

Goal: Determine whether switching the button from **Blue (A)** to **Green (B)** increases the Add-to-Cart rate.

This project highlights skills in:
- Data simulation & cleaning (Python, Pandas, NumPy)  
- Statistical analysis (two-proportion z-test)  
- Data visualization (Matplotlib, Seaborn)  
- Translating results into **business recommendations**

Experiment Details

Variants Tested:
- A: Blue Add-to-Cart button  
- B: Green Add-to-Cart button  

Metric:Add-to-Cart rate  

Sample Size: 1,000–20,000 users per variant (simulated for demonstration)


Key Results

- Conversion Rate A (Blue):** 12.0%  
- Conversion Rate B (Green):** 15.3%  
- Absolute Lift:** 3.3 pp  
- Relative Lift:** 27.5%  
- Statistical Significance:** p-value = 0.02  

Conclusion:
The green button improved Add-to-Cart conversions. Recommendation: roll out Green** to maximize conversions.

---

Dashboard / Visuals

All charts are saved in `dashboard/screenshots/` for quick reference:

- `conversion_rate_chart.png` — Shows A vs B conversion rates with 95% CI


 How to Use

1. Open the notebook `notebooks/ecommerce_ab_test_button_color.ipynb`  
2. Run all cells to simulate data, calculate rates, run the z-test, and generate visuals  
3. Review Markdown summary for clear business insights

---

Tools & Skills

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Statistical testing & hypothesis evaluation  
- Business-oriented data storytelling  
- Portfolio-ready visuals for stakeholder communication
