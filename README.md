<img width="1311" height="741" alt="Ảnh chụp màn hình 2026-10-21 124128" src="https://github.com/user-attachments/assets/98e7db31-a720-4dc8-8511-d95b517ad54f" />

# BIDV Financial Performance Dashboard (Power BI)

## The Context
Commercial banks often post impressive headline revenues, but a bigger balance sheet does not always mean a healthier bank. Over a 7-year timeline, a bank might grow its interest income while quietly letting operating expenses spiral or profit margins thin out.

Looking through BIDV's annual financial statements, I wanted to build a dashboard that looks past the surface numbers and focuses on operational efficiency. The goal was simple: make it immediately clear whether the bank was actually running better year-over-year, or just getting bigger.


## What the Dashboard Answers
Instead of crowding the screen with standard financial statement line items, the report focuses on four core indicators:

- Revenue vs. Cost Efficiency: Tracking Total Operating Income alongside Cost-to-Income Ratio to see if cost control kept pace with revenue expansion.
- Bottom-Line Health: Monitoring Net Profit Margin to evaluate how effectively income converts into actual profit.
- Shareholder Value: Following Earnings Per Share trends across economic cycles.


## Practical Design Choices
A common problem with banking dashboards is misinterpreting financial directional signs. A higher number is not always good news:

- Contextual YoY Comparisons: When selecting a specific year, the cards dynamically benchmark metrics against the prior year.
- Metric-Specific Signals: While revenue growth triggers a positive indicator, an increase in CIR represents rising overhead and correctly signals caution. 
- Clean Baseline: When looking at aggregate multi-year figures, comparison badges automatically clear so users are not misled by out-of-context percentage changes.


## File
The .pbix file is available in the repository, containing the underlying data model, relationships, and measures.

---
Author: VAN GIA BAO  
Contact: vgbao.24115@gmail.com
