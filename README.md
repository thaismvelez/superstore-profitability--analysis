# Superstore Profitability Analysis

## Project Overview

This project analyzes Superstore’s data to uncover opportunities for boosting profitability and minimizing losses. By examining profit centers, loss-makers, advertising effectiveness, and product return rates, the analysis delivers actionable insights to support data-driven strategic decision-making.

## Dataset

This analysis uses the Superstore.xls dataset, which includes detailed information on orders, product categories, shipping modes, regions, and returns. The Orders and Returns tables were joined and calculated fields were created to evaluate profitability and return behavior. Note: The original Tableau workbook used for visualizations became corrupted, so some visualizations may need to be rebuilt if replication is needed.

## Introduction

This project evaluates the Superstore’s sales performance to identify profitable product areas, pinpoint loss-driving items, and assess advertising opportunities. The goal is to develop data-driven strategies to increase overall profitability and help the store avoid bankruptcy.

## Project Objectives

1. Identify the highest profit-generating product subcategories and regions, as well as the biggest loss-makers.
2. Determine which individual products should be discontinued due to significant negative profit impact.
3. Recommend which product subcategories to prioritize and which to scale back.
4. Evaluate advertising opportunities by identifying the most profitable state and month combinations for targeted marketing.
5. Analyze product and customer return rates to assess their impact on overall profitability and operational performance.

## Methodology

- **Data Cleaning & Preparation:**
    - Worked with the Superstore dataset containing orders, product details, shipping information, and returns.
    - Performed data cleaning and standardized key fields.
    - Created a calculated **Returned** field by converting `Yes` values to 1 and `null` values to 0.
    - Joined the Orders and Returns tables using a **Left Join** to retain full transaction history.

- **Profit & Loss Analysis:**
    - Created visualizations comparing **sub-category performance by region** to identify major profit centers and loss areas.
    - Used product-level profit data to locate the lowest-performing products.
    - Compared subcategories across regions to recommend which to expand vs. discontinue.

- **Return Rate Analysis:**
    - Analyzed return rates at both the **product** and **customer** level to identify frequent return drivers.
    - Compared **average profit vs. average return rate** across product categories to evaluate long-term category sustainability.

- **Advertising & Regional Focus:**
    - Calculated average profit by **state and month** to determine when and where advertising would yield the best return.
    - Estimated recommended ad spend based on the guideline of allocating **20% of profits to advertising**.
 
## Visual Representation

**Profits and Losses by Sub-Category Across Regions**

This bar chart compares the profitability of key product sub-categories within each region. It highlights which products consistently drive revenue (such as Copiers, Phones, and Accessories) and which categories generate losses across regions (such as Bookcases and Tables). This visualization serves as the foundation for identifying high-value product areas and informing decisions on product discontinuation or strategic focus.

<img alt="Screenshot 2025-11-04 at 5 18 32 PM" src="https://github.com/user-attachments/assets/7a00b00a-d47d-4f81-a1e0-e7950f927421" width="600" height="400" />

**Lowest-Profit Products**

Displayed individual product-level losses to highlight items that should be discontinued. Key losses included the GBC DocuBind P400, Cubify CubeX 3D Printer, and Bush Racetrack Conference Table.

**Advertising Opportunities by State and Month**

A chart showing which state and month combinations offer the strongest profit potential for targeted advertising.

**Return Rates by Product and Customer**

Visuals displaying products and customers with the highest frequency of returns.

**Profit vs. Return Rate Comparison**

A visualization comparing average profit to return rates across product categories to assess which categories are most efficient.

## Key Findings

**Profit Centers:**

- The strongest profit centers are Copiers in the West and Copiers in the East, making them key product-region combinations to continue prioritizing.

**Loss-Making Products:**

- Tables in the East and Tables in the South are the top loss-making subcategory-region combinations.
- Specific products driving significant losses include:
    - GBC DocuBind P400 Electric Binding System (over $20k loss)
    - Cubify CubeX 3D Printer Double Head Print (over $8k loss)
    - Bush Advantage Collection Racetrack Conference Table (over $5k loss)
- These products should be considered for discontinuation to reduce overall losses.

**Subcategory Focus:**

- **Focus on:** Copiers, Phones, and Accessories — these categories show strong profitable performance.
- **Reduce or discontinue:** Tables, Bookcases, and Supplies — these categories consistently show negative profit performance.

**Advertising Recommendations:**

- Most cost-effective advertising opportunities were identified as:

    - **Vermont in November** (recommended budget ~$119.20)
    - **Rhode Island in December** (recommended budget ~$50)
    - **Indiana in October** (recommended budget ~$128.62)

**Return Rate Analysis:**

- Several technology products and a small group of repeat customers show disproportionately high return rates, suggesting targeted review of product quality, customer expectations, or return policies.

## Conclusion

Prioritizing high-performing subcategories like Copiers, Phones, and Accessories while phasing out loss-makers such as Tables, Bookcases, and Supplies will help strengthen overall profitability. Targeted advertising during peak months in Vermont, Rhode Island, and Indiana supports efficient budget use and increases return on ad spend. Additionally, monitoring products and customers with high return rates can reduce preventable losses and improve operational efficiency. Together, these strategies guide the Superstore toward more sustainable and profitable performance.

## Recommendations for Improvement

- **Discontinue Low-Performing Products:** Stop selling recurring loss-makers (e.g., GBC Binding System, CubeX 3D Printer, Bush Conference Table) to immediately reduce financial waste.
- **Refocus Product Strategy:** Shift sales and inventory emphasis toward Copiers, Phones, and Accessories, while scaling back Tables, Bookcases, and Supplies, which consistently generate losses.
- **Targeted Advertising:** Invest in advertising only in high-performing state-month combinations (Vermont in November, Rhode Island in December, and Indiana in October) to maximize return on ad spend.

## Future Directions

1. **Enhanced Customer Profiling:** Perform deeper segmentation to understand why certain customers exhibit higher return behaviors and tailor product recommendations or policies accordingly.
2. **Predictive Inventory Optimization:** Implement forecasting models to better manage stock levels, especially for products with historically high losses or return rates.
3. **Targeted Product Testing:** Before fully discontinuing product lines, run small-scale trials or limited region rollouts to validate demand and performance before making final decisions.



 


