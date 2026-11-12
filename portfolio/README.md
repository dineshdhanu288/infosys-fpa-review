# FP&A portfolio | Shanampuri Dinesh

Three self-initiated, AI-assisted finance case studies. The planning models use Infosys consolidated IFRS results in INR crore. The close simulation uses a fictional IT-services group.

| Project | Review the output | Files |
|---|---|---|
| Infosys FY27 budget vs actual | Q2 operating profit reached ₹10,330 crore against a simulated ₹9,576.47 crore budget. Constant-currency performance contributed ₹444.90 crore adverse; estimated currency translation and rounding added ₹4,086.65 crore. Higher expenses absorbed ₹2,888.22 crore. | [Excel workbook](Infosys_Budget_vs_Actual.xlsx) · [Power BI project](Budget_and_Forecast.zip) |
| Infosys three-statement forecast | FY27 combines reported H1 with forecast H2. Base FY27 revenue is ₹198,162.88 crore and closing cash is ₹24,801.49 crore. Change the case on Control to test the forecast. | [Excel workbook](Infosys_Three_Statement_Model.xlsx) |
| Month-end close and flux analysis | A 12-month simulated ledger contains 142 balanced journals, three deliberate posting errors and 144 reconciliation comparisons. March closes with ₹64.9420 crore of assets and ₹59.1272 crore of equity. | [Excel workbook](Month_End_Close.xlsx) · [Power BI project](Close_and_Flux.zip) |

## Review in two minutes

1. In the budget workbook, open **Bridge** and compare the Q2 operating-profit bridge with **Variance**. The quarterly budget was frozen using information available on 23 April 2026. The forward outlook uses October actuals.
2. In the forecast workbook, open **Model** and change **Control** from Base to Downside. Trace revenue through operating profit, receivables, operating cash flow and closing cash.
3. In the close workbook, open **Errors** and inspect the December insurance reclassification. The correcting entry changes the cost-line presentation and leaves profit unchanged.

The Power BI archives include the report pages, semantic model, DAX and embedded Power Query data. Extract each archive, open its `.pbip` file in Power BI Desktop and select **Home → Refresh**. Source figures and simulated forecasts are identified in the workbooks.

## Source documents

[Infosys FY26 consolidated IFRS statements](https://www.infosys.com/investors/reports-filings/quarterly-results/2025-2026/q4/documents/consolifrsinr-fy26-q4-and-12m-finstatement.pdf) · [April 2026 guidance](https://www.infosys.com/investors/reports-filings/quarterly-results/2025-2026/q4/documents/ifrs-inr-press-release.pdf) · [H1 FY27 consolidated IFRS statements](https://www.infosys.com/investors/reports-filings/quarterly-results/2026-2027/q2/documents/consolifrsinr-fy27-q2-and-h1-finstatement.pdf)

The budget, rolling forecast and three-statement projections are illustrative. The FX bridge applies rounded published constant-currency growth to prior-year INR revenue. The reported statements, forecast assumptions and ledger simulation have separate provenance.
