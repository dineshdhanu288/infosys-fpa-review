## Three FP&A portfolio projects

[Open the completed projects folder](../Completed-Projects/) · [Download all five working files](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/Completed-Projects/Completed_FPA_Portfolio.zip)


Click a project title to read its results here. Click an Excel or Power BI link to download the working file, then open it from Downloads. On a GitHub file page, **View raw** or the download arrow retrieves the original file.


| Project | Working files | Result to inspect |
|---|---|---|
| [1 · Infosys three-statement forecast](P1-Forecast/) | [Excel](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Infosys_Three_Statement_Model.xlsx) | FY27 base closing cash of ₹24,801.49 crore |
| [2 · Infosys budget variance](P2-Variance/) | [Excel](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Infosys_Budget_vs_Actual.xlsx) · [Download Power BI report](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Infosys_Budget_Review.pbix) | Q2 operating profit ₹753.53 crore above the simulated budget |
| [3 · IT services month-end close](P3-Close/) | [Excel](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Month_End_Close.xlsx) · [Power BI Desktop report](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Close_and_Flux.pbix) | 5.25 average business days across 12 simulated closes |

# FP&A portfolio | Shanampuri Dinesh

Three FP&A portfolio projects covering budgeting, forecasting and month-end close. The planning models use Infosys consolidated IFRS results in INR crore. The close simulation uses a fictional IT-services group.

| Project | Review the output | Files |
|---|---|---|
| Infosys FY27 budget vs actual | Q2 operating profit reached ₹10,330 crore against a simulated ₹9,576.47 crore budget. Constant-currency performance contributed ₹444.90 crore adverse; estimated currency translation and rounding added ₹4,086.65 crore. Higher expenses absorbed ₹2,888.22 crore. | [Excel workbook](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Infosys_Budget_vs_Actual.xlsx) · [Download Power BI report](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Infosys_Budget_Review.pbix) |
| Infosys three-statement forecast | FY27 combines reported H1 with forecast H2. Base FY27 revenue is ₹198,162.88 crore and closing cash is ₹24,801.49 crore. Change the case on Control to test the forecast. | [Excel workbook](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Infosys_Three_Statement_Model.xlsx) |
| Month-end close and flux analysis | A 12-month simulated ledger contains 142 balanced journals, three deliberate posting errors and 144 reconciliation comparisons. March closes with ₹64.9420 crore of assets and ₹59.1272 crore of equity. | [Excel workbook](https://github.com/dineshdhanu288/infosys-fpa-review/raw/refs/heads/main/portfolio/Month_End_Close.xlsx) · [Power BI project](Close_and_Flux.zip) |

## Review in two minutes

1. In the budget workbook, open **Bridge** and compare the Q2 operating-profit bridge with **Variance**. The quarterly budget was frozen using information available on 23 April 2026. The forward outlook uses October actuals.
2. In the forecast workbook, open **Model** and change **Control** from Base to Downside. Trace revenue through operating profit, receivables, operating cash flow and closing cash.
3. In the close workbook, open **Errors** and inspect the December insurance reclassification. The correcting entry changes the cost-line presentation and leaves profit unchanged.

Download the .pbix files and open them in Power BI Desktop. Both contain their data.

## Source documents

[Infosys FY26 consolidated IFRS statements](https://www.infosys.com/investors/reports-filings/quarterly-results/2025-2026/q4/documents/consolifrsinr-fy26-q4-and-12m-finstatement.pdf) · [April 2026 guidance](https://www.infosys.com/investors/reports-filings/quarterly-results/2025-2026/q4/documents/ifrs-inr-press-release.pdf) · [H1 FY27 consolidated IFRS statements](https://www.infosys.com/investors/reports-filings/quarterly-results/2026-2027/q2/documents/consolifrsinr-fy27-q2-and-h1-finstatement.pdf)

The budget, rolling forecast and three-statement projections are illustrative. The FX bridge applies rounded published constant-currency growth to prior-year INR revenue. The reported statements, forecast assumptions and ledger simulation have separate provenance.

### Infosys | Budget versus actual
FY27 · Simulated April budget compared with sourced quarterly IFRS actuals · INR crore

### Q1 FY27 performance

| Line | Budget | Actual | Profit impact |
|---|---|---|---|
| Revenue | 43,335.97 | 48,211.00 | 4,875.03 |
| Cost of sales | 29,989.29 | 33,033.00 | -3,043.71 |
| Selling and marketing | 2,182.33 | 2,568.00 | -385.67 |
| Administration | 2,063.80 | 2,447.00 | -383.20 |
| Operating profit | 9,100.55 | 10,163.00 | 1,062.45 |

### Q2 FY27 performance

| Line | Budget | Actual | Profit impact |
|---|---|---|---|
| Revenue | 45,602.25 | 49,244.00 | 3,641.75 |
| Cost of sales | 31,557.60 | 33,943.00 | -2,385.40 |
| Selling and marketing | 2,296.45 | 2,489.00 | -192.55 |
| Administration | 2,171.73 | 2,482.00 | -310.27 |
| Operating profit | 9,576.47 | 10,330.00 | 753.53 |

### Q2 operating-profit bridge

| Step | INR crore |
|---|---|
| Budget OP | 9,576.47 |
| CC performance | -444.90 |
| FX and rounding estimate | 4,086.65 |
| Cost of sales | -2,385.40 |
| Selling | -192.55 |
| Administration | -310.27 |
| Reported rounding | 0.00 |
| Actual OP | 10,330.00 |

### Infosys | Three-statement forecast
Base scenario · FY26 actual and FY27-FY29 projections · INR crore

### Statement summary

| Line | FY26 actual | FY27 blend | FY28 forecast | FY29 forecast |
|---|---|---|---|---|
| Revenue | 178,650.00 | 198,162.88 | 217,202.28 | 238,070.96 |
| Operating profit | 36,254.00 | 41,359.57 | 45,001.48 | 49,325.20 |
| Net profit | 29,474.00 | 32,353.08 | 36,103.90 | 39,572.74 |
| Operating cash flow | 35,824.00 | 33,478.93 | 39,837.48 | 42,505.26 |
| Investing cash flow | 108.00 | -6,035.44 | -3,110.97 | -3,409.87 |
| Financing cash flow | -39,786.00 | -24,866.99 | -25,990.79 | -28,487.97 |
| Closing cash | 22,201.00 | 24,801.49 | 35,537.22 | 46,144.63 |
| Total assets | 155,967.00 | 169,034.06 | 183,425.55 | 199,621.76 |
| Total liabilities | 62,670.00 | 63,346.86 | 64,486.95 | 66,158.56 |
| Equity | 93,297.00 | 105,687.20 | 118,938.61 | 133,463.20 |
| Balance check | 0.00 | -0.00 | -0.00 | 0.00 |

### FY27 scenario comparison

| Line | Downside | Base | Upside |
|---|---|---|---|
| Revenue | 194,907.53 | 198,162.88 | 200,649.51 |
| Operating profit | 40,609.47 | 41,359.57 | 42,162.24 |
| Net profit | 31,756.81 | 32,353.08 | 32,976.08 |
| Closing cash | 25,936.27 | 24,801.49 | 25,159.69 |

### IT services | Month-end close
Simulated two-entity ledger · April 2025 to March 2026 · INR crore

### Monthly performance and sign-off

| Month ended | Revenue | Expense | Pre-tax profit | Close days |
|---|---|---|---|---|
| 2025-04-30 | 8.00 | 5.88 | 2.12 | 5 |
| 2025-05-31 | 8.18 | 5.99 | 2.19 | 5 |
| 2025-06-30 | 8.86 | 6.44 | 2.42 | 6 |
| 2025-07-31 | 8.54 | 6.23 | 2.31 | 5 |
| 2025-08-31 | 8.72 | 6.35 | 2.37 | 5 |
| 2025-09-30 | 9.40 | 6.88 | 2.52 | 6 |
| 2025-10-31 | 9.08 | 6.59 | 2.49 | 5 |
| 2025-11-30 | 9.26 | 6.71 | 2.55 | 5 |
| 2025-12-31 | 9.94 | 7.16 | 2.78 | 6 |
| 2026-01-31 | 9.62 | 6.95 | 2.67 | 5 |
| 2026-02-28 | 9.80 | 7.06 | 2.74 | 5 |
| 2026-03-31 | 10.48 | 7.51 | 2.97 | 5 |
| Year / average | 109.88 | 79.75 | 30.13 | 5.25 |

### March closing balances

| Assets | Liabilities | Equity | Balance check |
|---|---|---|---|
| 64.94 | 5.81 | 59.13 | 0.00 |

### Corrections posted

| Month | Issue | Amount |
|---|---|---|
| 2025-06-30 | Duplicate vendor invoice | 1.20 |
| 2025-09-30 | Unrecorded bank fee | 0.08 |
| 2025-12-31 | Insurance charged to rent | 0.20 |

