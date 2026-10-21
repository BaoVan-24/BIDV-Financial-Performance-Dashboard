<img width="1311" height="741" alt="Ảnh chụp màn hình 2026-10-21 124128" src="https://github.com/user-attachments/assets/98e7db31-a720-4dc8-8511-d95b517ad54f" />

# BIDV-Financial-Performance-Dashboard
Hi there! Welcome to my financial data project. I built this Power BI dashboard to analyze the financial health of BIDV, one of Vietnam's largest commercial banks, spanning a 7-year period.

My goal here wasn't just to plot standard charts, but to create a highly readable, practical tool that instantly tells a story about the bank's operational efficiency. The dashboard focuses on core banking metrics that actually matter: Total Operating Income, Profit Margin, Cost-to-Income Ratio, and Earnings Per Share trends.

How I built it

I used Power BI as the primary visualization tool, but the real engine behind this dashboard is the data modeling and advanced DAX logic.

One of the technical pieces I am most proud of in this project is the dynamic conditional formatting for the KPI cards. Instead of relying on Power BI's default settings, I wrote custom DAX measures utilizing functions like HASONEVALUE, CALCULATE, and REMOVEFILTERS to create a smart Year-over-Year comparison system.

When you select a specific year, the dashboard automatically looks back at the previous year and updates the indicators. It dynamically generates directional arrows and semantic colors based on business logic. For example, a revenue increase shows a green up-arrow, but a CIR increase (which indicates rising operational costs) correctly triggers a red up-arrow. I also programmed the logic to smoothly revert to a clean, neutral state when viewing the all-time totals, preventing any misleading color highlights.

A quick look at the result

Feel free to download and explore the raw .pbix file in this repository to see how the DAX measures and data models are structured behind the scenes. If you are a recruiter, a fellow data enthusiast, or just curious about business intelligence, I would be happy to connect and chat!
