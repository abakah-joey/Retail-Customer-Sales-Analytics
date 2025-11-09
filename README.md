# Retail-Customer-Sales-Analytics
This Excel analytics project examined the relationship between retail sales performance, customer demographics, and product categories.

EXECUTIVE SUMMARY
- This Excel analytics project examined the relationship between retail sales performance, customer demographics, and product categories using a dataset of 1,000 transactions. The analysis followed a structured process that included data cleaning, feature engineering, formula application, and exploratory analysis using pivot tables. A dynamic Excel dashboard was developed to visualize key KPIs, revenue trends, and the influence of demographic and product factors on overall sales performance.


PROBLEM STATEMENT
- The project seeks to determine how customer demographics and product categories affect total revenue over time. It further explores monthly sales trends to uncover patterns that can guide strategic business decisions and marketing focus.



DATA UNDERSTANDING

- Dataset sourced from a retail sales CSV file.
- 1,000 distinct transaction records, 9 columns, 1001 rows including header.

- Key fields: Total Amount, Product Category, Age, Gender, Date.
- Dataset unchanged; no additions, deletions, or assumptions.



METHODOLOGY

DATA CLEANING

- Checked for duplicates; none found.
- Checked for missing values; none found.
- Standardized date format to Date.
- Verified Total Amount = Quantity × Unit Price.

FEATURE ENGINEERING

- Created an Age Group using Excel formula =IFS.
- Extracted Month from Date using =TEXT.
- New fields were pasted as values and converted into an Excel table.
  
<img width="1916" height="734" alt="Screenshot 2025-11-09 140817" src="https://github.com/user-attachments/assets/4ce35b00-7f65-4901-b777-c1a42b051ebd" />

<img width="1917" height="976" alt="Screenshot 2025-11-09 141009" src="https://github.com/user-attachments/assets/0981f7ed-21a9-4f04-b13f-ced6b547404f" />

  


EXPLORATORY DATA ANALYSIS

Pivot tables were used to:
- Simplify data for dashboard visualization.
- Derive descriptive KPIs and trends.
<img width="1910" height="980" alt="Screenshot 2025-11-09 141100" src="https://github.com/user-attachments/assets/21dfdc61-9f30-44d6-a75a-7218d321b67e" />
<img width="1912" height="973" alt="Screenshot 2025-11-09 141209" src="https://github.com/user-attachments/assets/b79956f9-e597-462f-8ef6-de40c34154e3" />

  

KPIs included:
- Total Revenue
- Total Stock Sold
- Total Transactions
- Average Customer Age

VISUALIZATION

Excel dashboard designed with:
- Rectangle shapes and pivot charts.
- Slicers for Product Category and Quantity Purchased.
- Dual-tone color scheme using black and light green for visual balance.
<img width="1848" height="848" alt="Screenshot 2025-11-09 140647" src="https://github.com/user-attachments/assets/c7dbcf7c-b705-4998-8787-85ae65280ad6" />

  

DISCUSSION AND INTERPRETATION

- Total revenue of 456,000 was generated from 2,514 items sold.
- Gender contribution: Males accounted for 51 percent of total revenue, females 49 percent, indicating a near-balanced spending pattern.
  
Revenue by age group (ascending order):
 - Gen Z < Pre-Retirees < Gen Y < Millennials < Gen X
 This indicates stronger purchasing power among older demographics.

Top contributing age group by product category:
- Clothing: Millennials
- Beauty: Gen X
- Electronics: Pre-Retirees

Highest quantity purchased per sale (4 items):
- Gender-wise: Females led with total revenue of 94,940, about 4,020 more than males.
- Age-wise: Millennials dominated with a 24 percent lead in corresponding revenue.

Monthly sales trend:
- Revenue showed both uptrends and downtrends throughout the year.
- May recorded the highest peak of approximately 53,000, suggesting a strong mid-year buying season.
- September experienced the lowest performance of approximately 24,000, marking the weakest sales month.

- Above-average months: February, May, October, and December.
- Below-average months: March and September.
- Near-average months: January, April, June, July, August, and November.

- Overall, Millennials and Gen X are the main drivers of revenue, while female shoppers contribute strongly to high-volume purchases. Seasonal sales shifts indicate potential to optimize marketing and promotional efforts during lower-performing months.

RECOMMENDATIONS AND ACTIONABLE INSIGHTS

1. Gen Z Segment
- Contributed 74,650, representing 16.4 percent of total revenue.
- Beauty-related purchases formed the majority of their spending pattern.
- Targeted advertising campaigns and product discounts on beauty, skincare, and wellness products are recommended.
- Leveraging social media influencers and limited-time promotional bundles could further drive brand interaction and repeat purchases.

2. Millennial Segment
- Generated 97,090, accounting for 21.3 percent of total revenue, with ₵41,640 spent on clothing out of 155,580 total clothing revenue.
- Marketing should emphasize modern fashion trends, corporate-style outfits, and seasonal collections across Instagram, TikTok, and Pinterest.
- Introducing loyalty programs or early access sales could sustain momentum and encourage long-term brand loyalty.

3. Gen X and Pre-Retiree Segments
- Gen X generated 97,235, with 35,950 spent on beauty products out of 143,515 total.
- Marketing should focus on premium, rejuvenation-oriented beauty lines, supported by trust-based branding and expert-backed product information.
- Pre-Retirees produced 90,190, leading the electronics category with 38,210 of the total 156,905.

Messaging should highlight ease of use, time-saving features, and energy efficiency.

4. Seasonal Sales Optimization
- Low-performing months, such as March and September, should incorporate discount campaigns, flash sales, and social media initiatives to stimulate purchases.
- High-peak months, such as May, should include inventory expansion, proactive logistics planning, and timely restocking to meet increased demand.


CONCLUSION

This Excel analytics project successfully analyzed 1,000 transactions to uncover how customer demographics and product categories influence total revenue. 

Key findings include:
- Revenue Drivers: Millennials and Gen X are the main contributors, with female customers leading high-volume purchases.
- Product Preferences: Clothing is dominated by Millennials, beauty products by Gen X, and electronics by Pre-Retirees.

- Seasonal Trends: Revenue peaks in May and dips in September, providing clear opportunities for seasonal marketing optimization.

Actionable Takeaways:
- Target Gen Z with beauty-focused campaigns and influencer-led promotions.
- Sustain Millennial purchases through fashion trend-focused marketing, loyalty programs, and early access promotions.
- Capitalize on Gen X and Pre-Retiree segments with premium skincare and electronics messaging.

- Implement seasonal sales strategies to optimize performance across low- and high-performing months and maximize revenue impact.


FUTURE ANALYSIS RECOMMENDATIONS

- Examine the impact of discounting on profitability.
- Explore repeat purchase rates to improve customer retention.
- Integrate marketing spend and campaign effectiveness for a holistic view of sales performance

