## Apple Inc. Financial Intelligence Dashboard | Power BI, DAX, Power Query | 2025
Designed and developed a 5-page interactive financial analysis dashboard for Apple Inc. (FY2019–FY2025) using Microsoft Power BI, modelling data across all three financial statements sourced from SimFin.

- Built a star schema data model connecting Income Statement, Balance Sheet, and Cash Flow fact tables to a Date dimension, with 20+ DAX measures covering profitability, liquidity, leverage, and efficiency ratios (Gross Margin%, Net Margin%, ROE, ROA, Current Ratio, Quick Ratio, D/E, FCF Margin%)

- Developed dynamic waterfall charts for income decomposition (Revenue → Gross Profit → Operating Income → Net Income) and cash flow analysis (OCF → CapEx → FCF) using a stacked bar technique with invisible base measures — workaround for Power BI's native waterfall limitations

- Implemented a Financial Health Scorecard matrix with context-aware conditional formatting driven by a single DAX SWITCH measure routing per-ratio thresholds dynamically across all 7 fiscal years

- Derived key financial insights including Apple's sub-1.0 Current Ratio offset by $100B+ OCF, ROE exceeding 150% as a buyback artifact, and $110B+ annual capital returns as the primary driver of negative financing cash flow
