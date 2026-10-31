[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Family Loan & Fund Flow Reconciliation Toolkit: Running Balance & Interest Calculator Excel Template

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](#license)
[![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)](#access)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Financial%20Reconciliation%20Spreadsheet-orange.svg)](#what-it-helps-track)

**A comprehensive family loan tracker and fund flow reconciliation spreadsheet. Reconstruct years of two-way inter-family money transfers into a traceable running principal balance, automatically calculate accrued interest, and generate a transparent audit trail for personal financial agreements.**

> **Try the free web-based calculator. For users requiring permanent financial records, offline audit trails, and repeated monthly account servicing, you can download the fully unlocked Excel template with a 30-day money-back guarantee.**
>
> 🌐 Open in Browser → [Try the Free Inter-Family Loan Tracker Web App (Live Demo)](https://hyvoid.github.io/family-loan-tracker-excel/)
> 
> 📥 Download Template → [Download the Reusable Excel Template for Family Loan Reconciliation (Offline Version)](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation)  

## Core Features: Pain Points vs. Tracking Solutions

Instead of tracking cumulative transfers that fail to show the true financial position, this toolkit converts scattered bank records into a standardized loan amortization schedule.

| Common Tracking Pain Point (The Problem) | How This Calculator Solves It (The Solution) |
| :--- | :--- |
| **Lost track of historical money lent vs. repaid** | Segregates historical cash advances from partial repayments across the entire transaction ledger. |
| **Messy bank statements entered out of sequence** | Automatically reconstructs the **running principal balance** dynamically, regardless of data entry order. |
| **Flat interest applied to changing balances** | Calculates **accrued interest** precisely over each outstanding period based on the exact daily balance. |
| **Fluctuating historical inflation or market rates** | Applies customizable historical market-rate schedules, matching specific interest rates to their exact effective periods. |
| **Unexplained lump-sum final balances** | Splits the current outstanding total into distinctly auditable columns: **Principal vs. Accrued Interest**. |
| **Manually extending formulas for new payments** | Auto-extends the calculation date to "Today," rolling over the current total outstanding automatically. |

## Quick Start Tutorial: How to Reconstruct Your Financial Records

Follow this workflow to transform disorganized financial history into a clean, auditable balance sheet. 

**Step 1: Configure Loan & Interest Parameters**
Define your financial baseline in the Parameters dashboard. Set the currency symbol, day-count basis (e.g., Actual/365), compounding interest method, and map out the historical market-rate schedule (e.g., matching the IRS Applicable Federal Rates or custom agreed rates).

**Step 2: Import Your Historical Transaction Ledger**
Paste your raw financial data into the input table. The system requires only basic data points: Transaction ID, Date, Transfer Direction (Inflow/Outflow), Amount, and a brief Memo. You can directly copy-paste this from your bank export CSVs.

**Step 3: Generate the Chronological Balance Schedule**
Let the dynamic calculation engine process the data. It will automatically sort all records chronologically, standardize positive/negative cash flows, rebuild the daily running principal, and calculate the exact interest accrued between each payment period.

**Step 4: Maintain Ongoing Repayment Records**
As new payments are made, simply append them to the bottom of the ledger. The engine instantly recalculates the accrued interest and total outstanding balance up to the current date.

👉 **Ready to build a permanent record?** [Download the Excel Template](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation) to securely store your private financial data offline and reuse the calculation engine for ongoing monthly reconciliation.

## Why I Built This Family Fund Reconciliation Tool

Long-running family financial arrangements (like parents funding a child's down payment, or siblings co-financing a property) often develop without the rigid structure of a formal loan servicing system.

Money moves in both directions over the years. Records accumulate across bank statements, WhatsApp messages, and memory. Eventually, the hardest question isn't *“How much money moved?”* It is:

**“What was the exact outstanding balance on any given historical date, and how much interest should have accrued against that specific balance?”**

A simple `SUM()` of transfers in a basic spreadsheet cannot answer this. If records contain multiple cash advances followed by sporadic partial repayments, a basic total ignores the *time value of money* and the duration each dollar remained unpaid. 

This toolkit productizes the financial reasoning behind complex accounting. It turns a decade of messy, mixed transactions into a strictly chronological, defensible calculation framework.

## Automated Spreadsheet vs. Manual Ledger Accounting

| Manual Accounting Hurdles (Without Tool) | Automated Excel Reconciliation (With Tool) |
| :--- | :--- |
| **Disorganized Chronology:** Calculating running balances against out-of-order ledger entries causes compounding math errors. | **Automated Sorting:** The calculation engine reorders the full transaction history by date prior to applying interest formulas. |
| **Inconsistent Cash Flow Signs:** Manually deciding if a transfer is a positive or negative adjustment leads to formula breaks. | **Standardized Cash Flows:** Transaction directions (Advances vs. Repayments) are parsed into a strict accounting movement convention. |
| **Static Interest Errors:** Applying a single flat interest rate against a dynamic multi-year balance overcharges or undercharges interest. | **Dynamic Period Accrual:** Compound or simple interest is calculated specifically across each distinct historical outstanding period. |
| **Rate Obscurity:** Using a single blended rate hides the reality of changing macroeconomic interest rates over a decade. | **Variable Rate Mapping:** Each transaction period is automatically matched via lookup to the user-defined effective market rate schedule. |
| **Data Commingling:** Mixing principal and interest in one column makes the final debt number impossible to audit or explain to family. | **Data Segregation:** Principal balances, accrued interest limits, and total outstanding liabilities are calculated in isolated, transparent columns. |

## Target Users & Specific Use Cases

This spreadsheet is engineered for individuals managing long-term financial relationships where historical transactions must be reverse-engineered into a mathematically sound balance and interest schedule. 

**Search & Match Your Persona:**
* **Parents & Guardians:** Tracking the *"Bank of Mom & Dad"* cash advances, managing personal loan repayment templates for children with transparent interest terms.
* **Executors & Estate Trustees:** Reconciling historical inter-family loans, documenting inherited debts, and generating audit trails for probate or family trust distributions.
* **Family Office Managers:** Operating an inter-entity fund flow tracker to monitor informal capital injections and drawdowns across family-owned businesses.
* **Siblings & Co-Investors:** Maintaining an informal joint-investment ledger to track who paid for what over years of shared property ownership or business ventures.
* **Personal Finance DIYers:** Anyone needing a robust alternative to complex bookkeeping software (like QuickBooks) to settle long-term peer-to-peer (P2P) lending ledgers.

*(Note: This toolkit provides decision-support calculations. It does not replace certified public accounting (CPA) services, formal legal loan documentation, or tax compliance advisory.)*

## About the Architecture

I build lightweight operational trackers and decision-support templates for environments that have too many moving parts for mental math, but lack the complexity to justify enterprise ERP software. 

The core design philosophy is simple: **Information must be structured chronologically to make the next financial decision confidently.** 

This toolkit rejects generic bookkeeping. It is a narrowly focused engine designed exclusively for reconstructing timelines, mapping variable interest rates, and proving the exact current outstanding position of private funds.

## Technical Details

<details>
<summary>For technical reviewers, Excel practitioners, and collaborators</summary>

### Workbook Architecture

The workbook uses five sheets across four functional layers:

| Sheet             | Role                                                                                                  | Input / Output                     |
| ----------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `00_Instructions` | System instructions, version information, and operating guidance                                      | Static                             |
| `01_Parameters`   | Global assumptions, direction definitions, day-count basis, interest method, and market-rate schedule | Manual input                       |
| `02_Transactions` | Historical two-way fund movement ledger                                                               | Manual input + dynamic calculation |
| `03_CalcEngine`   | Chronological reconstruction, running principal, rate matching, day counts, and interest engine       | Formula-driven                     |
| `04_Summary`      | Current outstanding balance and principal/interest breakdown                                          | Formula-driven                     |

The core data flow is:

```text
01_Parameters
      │
      ├──────────────┐
      │              ▼
      │       02_Transactions
      │              │
      │              ▼
      └──────► 03_CalcEngine
                     │
                     ▼
                 04_Summary
```

The calculation engine performs four major operations:

1. Sort historical transactions chronologically.
2. Convert each transaction into a standardized signed movement.
3. Reconstruct the running principal and match the applicable market rate.
4. Calculate period interest and accumulated outstanding interest.

The summary then extracts the latest principal and accrued-interest results to present the current outstanding position. The source architecture explicitly defines the transaction-to-engine-to-summary dependency chain.  

### Three Traps That Catch Even Experienced Financial Record Keepers

#### Trap 1 — Treating cumulative transfers as the whole answer

**1. A decision was made:**
Determine the amount currently outstanding by subtracting total repayments from total advances.

**2. The unnoticed flaw:**
This establishes the net principal but says nothing about how long different balances remained outstanding.

**3. Why it changes the result:**
Interest depends on both principal and elapsed time.

**4. Why the reasoning is incomplete:**
A $10,000 balance outstanding for several years is economically different from a $10,000 balance that appeared recently.

**5. Corrected approach:**
Reconstruct the running principal after every transaction and calculate each interval separately.

**6. Corrected outcome:**
The current result contains both the remaining principal and the accumulated interest attributable to the historical periods.

<details>
<summary>Formula logic</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

This creates a running principal balance from the standardized transaction movement vector.

</details>

#### Trap 2 — Applying one interest rate to the entire history

**1. A decision was made:**
Apply today's assumed market rate to the entire historical balance.

**2. The unnoticed flaw:**
The applicable rate may have changed during the historical period.

**3. Why it changes the result:**
Different periods can carry different annual rates.

**4. Why the reasoning is incorrect:**
A current rate does not automatically represent every historical period.

**5. Corrected approach:**
Maintain an effective-date rate schedule and match each transaction date against the applicable historical rate.

**6. Corrected outcome:**
Each period is calculated using the rate defined as effective at that point in the timeline.

<details>
<summary>Formula logic</summary>

```excel
=MAP(A2#, LAMBDA(d,
    XLOOKUP(
        d,
        '01_Parameters'!$A$13:$A$20,
        '01_Parameters'!$B$13:$B$20,
        0,
        -1
    )
))
```

The `-1` match mode retrieves the exact effective date or the next smaller effective date.

</details>

#### Trap 3 — Calculating interest without reconstructing the time intervals

**1. A decision was made:**
Calculate interest from one transaction date to a fixed settlement date.

**2. The unnoticed flaw:**
Subsequent transactions may have changed the outstanding principal during that period.

**3. Why it changes the result:**
Interest should reflect the balance applicable during each interval.

**4. Why the reasoning is incorrect:**
A single date-to-date calculation ignores changes in principal between transactions.

**5. Corrected approach:**
Calculate the number of days from each transaction to the next transaction, using today as the endpoint for the final open period.

**6. Corrected outcome:**
Interest follows the reconstructed historical balance rather than an assumed static amount.

<details>
<summary>Formula logic</summary>

```excel
=LET(
    dates, A2#,
    n, ROWS(dates),
    MAP(SEQUENCE(n), LAMBDA(i,
        IF(
            i = n,
            TODAY() - INDEX(dates, i),
            INDEX(dates, i + 1) - INDEX(dates, i)
        )
    ))
)
```

The final transaction continues accruing through the current date.

</details>

### Example Scenario

Consider a simplified historical sequence:

| Date       | Direction |  Amount |
| ---------- | --------- | ------: |
| 2020-01-15 | Advance   | $20,000 |
| 2020-09-01 | Advance   | $10,000 |
| 2021-06-15 | Repayment |  $8,000 |
| 2022-03-01 | Repayment |  $5,000 |

The standardized movement becomes:

```text
2020-01-15    +20,000
2020-09-01    +10,000
2021-06-15     -8,000
2022-03-01     -5,000
```

The running principal therefore becomes:

```text
After 2020-01-15    $20,000
After 2020-09-01    $30,000
After 2021-06-15    $22,000
After 2022-03-01    $17,000
```

The important analytical change is that interest is not calculated against $17,000 for the entire historical period.

Instead, the engine recognizes different balance intervals:

```text
$20,000  →  until 2020-09-01
$30,000  →  until 2021-06-15
$22,000  →  until 2022-03-01
$17,000  →  from 2022-03-01 → today
```

If the market-rate schedule changes between these dates, the rate applicable to each interval is determined from the effective-date table.

The resulting output separates:

```text
Net Outstanding Principal
+ Accrued Interest
----------------------
Current Total Outstanding
```

This makes the final number explainable: it can be traced back to the transaction sequence, balance intervals, rate assumptions, and elapsed days rather than being a manually entered settlement figure.

### Formula Reference

<details>
<summary>Transaction Direction → Net Movement</summary>

```excel
=LET(
    tx_dates, FILTER(A2:A10000, A2:A10000<>""),
    dirs, FILTER(C2:C10000, A2:A10000<>""),
    amts, FILTER(D2:D10000, A2:A10000<>""),
    out_dir, '01_Parameters'!$B$8,
    in_dir, '01_Parameters'!$B$9,
    MAP(
        dirs,
        amts,
        LAMBDA(d, a,
            IF(d=out_dir, a, IF(d=in_dir, -a, 0))
        )
    )
)
```

**Purpose:** Converts transaction directions into a standardized signed movement.

**Logic:** The configured advance/outflow direction becomes positive; the configured repayment/inflow direction becomes negative.

</details>

<details>
<summary>Chronological Transaction Sorting</summary>

```excel
=LET(
    raw_dates, FILTER('02_Transactions'!B2:B10000, '02_Transactions'!A2:A10000<>""),
    raw_mvmt, FILTER('02_Transactions'!E2:E10000, '02_Transactions'!A2:A10000<>""),
    SORTBY(
        HSTACK(raw_dates, raw_mvmt),
        raw_dates,
        1
    )
)
```

**Purpose:** Ensures historical transactions are processed chronologically regardless of their original input order.

</details>

<details>
<summary>Running Principal</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

**Purpose:** Builds the running principal balance from the standardized movement sequence.

</details>

<details>
<summary>Historical Market Rate Matching</summary>

```excel
=MAP(A2#, LAMBDA(d,
    XLOOKUP(
        d,
        '01_Parameters'!$A$13:$A$20,
        '01_Parameters'!$B$13:$B$20,
        0,
        -1
    )
))
```

**Purpose:** Matches each transaction date to the applicable effective market rate.

**Important:** The effective-date table must be maintained as an ordered rate schedule.

</details>

<details>
<summary>Period Days</summary>

```excel
=LET(
    dates, A2#,
    n, ROWS(dates),
    MAP(SEQUENCE(n), LAMBDA(i,
        IF(
            i = n,
            TODAY() - INDEX(dates, i),
            INDEX(dates, i + 1) - INDEX(dates, i)
        )
    ))
)
```

**Purpose:** Determines the number of days represented by each calculation interval.

</details>

<details>
<summary>Period Interest</summary>

```excel
=LET(
    principals, C2#,
    rates, D2#,
    days, E2#,
    day_base, '01_Parameters'!$B$4,
    principals * rates * (days / day_base)
)
```

**Purpose:** Calculates interest for each period using the reconstructed principal, matched rate, elapsed days, and configured day-count basis.

</details>

<details>
<summary>Accrued Interest</summary>

```excel
=SCAN(0, F2#, LAMBDA(prev_int, curr_int, prev_int + curr_int))
```

**Purpose:** Accumulates all historical period interest into the current accrued-interest balance.

</details>

<details>
<summary>Total Running Outstanding</summary>

```excel
=C2# + G2#
```

**Purpose:** Combines running principal and accrued interest at each calculation point.

</details>

### Validation Rules

| Field / Area              | Rule                                                                | Error Behavior                                                      |
| ------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Transaction ID            | Should identify each historical transaction uniquely                | Duplicate IDs require review                                        |
| Date                      | Must contain a valid transaction date                               | Invalid or blank dates can prevent correct chronological processing |
| Direction                 | Must match one of the configured direction definitions              | Unrecognized text can produce an incorrect movement                 |
| Amount                    | Historical transaction amount should be a positive absolute value   | Negative source amounts can reverse the intended sign convention    |
| Effective Date            | Must represent the beginning of a rate period                       | Incorrect dates can assign the wrong historical rate                |
| Annual Rate               | Must be entered as an annual percentage                             | Incorrect formatting changes the interest calculation               |
| Day-count basis           | Supported configuration is typically 360 or 365                     | Invalid configuration changes period interest                       |
| Dynamic-array output area | Must remain unobstructed                                            | Blocking cells produce `#SPILL!`                                    |
| Calculation mode          | Excel should remain in Automatic calculation mode                   | Manual mode can leave displayed results stale                       |
| Direction labels          | Parameter definitions and transaction selections must match exactly | Mismatched text can reverse or zero-out movement                    |

The source design specifically identifies dynamic-array spill conflicts, manual calculation mode, direction-label mismatches, and formatting problems as operational troubleshooting cases. 

</details>

## The Business Logic & Methodology

The model is built around a simple commercial principle: **a historical financial balance is a timeline, not just a total.**

Several methods work together:

* **Transaction normalization** converts different transaction directions into one consistent movement convention. This prevents the same financial event from being interpreted differently in different parts of the workbook.
* **Running-balance reconstruction** shows how the outstanding principal changed after every transaction. This makes partial repayments and additional advances visible rather than burying them in a cumulative total.
* **Period-based interest calculation** ties interest to the balance that actually existed during each period. The result is more traceable than applying one rate to one end-of-period balance.
* **Effective-date rate matching** allows historical market-rate assumptions to change over time. A new rate can be introduced without rebuilding the historical transaction ledger.
* **Principal-and-interest separation** makes the settlement figure explainable. The decision-maker can distinguish the amount of principal still outstanding from the interest accumulated under the selected assumptions.

The result is a practical reconciliation workflow: reconstruct the historical position first, apply the stated assumptions second, and present the current balance only after the underlying timeline has been established.

## Other Tools in This Series

Related lightweight business and financial decision-support tools are available across the project collection.

* **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — Why is cash always tight? — Forecast future liquidity under changing operational and financial assumptions.
* **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — Which trade flows are actually profitable after currency effects? — Measure multi-currency trade profitability across cross-border operations.
* **[RTL_Loan_Sizer_Pricer](https://github.com/HyVoid/RTL_Loan_Sizer_Pricer)** — What financing structure is supportable under different borrower and collateral scenarios? — Compare lending scenarios using risk-adjusted financing assumptions.
* **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — Where is personal and business cash being mixed or misallocated? — Separate personal and business cash flows into independently tracked budget tracks.
* **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — Does this real estate acquisition still create equity value after renovation and operating assumptions? — Evaluate multifamily acquisition returns under renovation financing and operating scenarios.
* **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — What is a property worth under different valuation methods? — Calculate property value across multiple valuation methods with tax and capital expenditure modeling.
* **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — Are shared costs being allocated fairly across entities or are some assets overburdened while others escape their true cost exposure? — Distribute supplier invoices across multiple legal entities and operating assets using configurable allocation methodologies.
* **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — What is each participant actually owed based on their entry timing and current pool value? — Track investment pool ownership continuously using NAV-based unit accounting.
* **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — Which operational commitments will create a cash problem in the next twelve weeks? — Connect Shopify sales bank transactions advertising spend and inventory purchasing into a unified cash flow decision framework.
* **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — Has enough meaningful information changed to justify a pricing adjustment? — Govern pricing recommendations through configurable guard rails that prevent unnecessary revenue volatility.
* **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — What actually changed in the business this period and which products or keywords drove the change? — Transform Amazon Seller Central SQP and Sellerboard exports into standardized executive business reviews.
* **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — Which products are actually profitable after all manufacturing costs are allocated and which are destroying margin? — Allocate factory labor utilities overhead and material costs to every SKU for true unit manufacturing economics.
* **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — Which orders are actually profitable after all hidden costs and where is money leaking across channels and currencies? — Reconstruct true order-level profitability by reconciling sales payouts shipping costs payment fees and marketplace commissions across multi-channel e-commerce operations.
* **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — Which contractor projects and customers are actually profitable after all job costs? — Connect lead estimation, job execution, and actual cost tracking into a unified contractor profitability framework.
* **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — Is the shop genuinely profitable after all ingredient, labor, and operating costs? — Connect recipe costing, sales, inventory consumption, and operating expenses into a unified profitability and cash flow framework.
* **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — Which freight bookings are actually profitable after all costs, fees, and currency conversion? — Measure booking-level freight profitability by reconciling revenue, COGS, bank fees, and container costs across mixed-currency transactions.
* **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — Which containers and customers are actually profitable across customs and fleet operations? — Consolidate customs clearance and fleet execution data into a single container-level profitability view.
* **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — What will our financial statements look like under different operating and financing scenarios? — Forecast integrated financial statements by linking revenue, expenses, working capital, and debt into a unified model.
* **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — How much of each building's reported margin is actually generated by that building versus by the way corporate costs were allocated? — Allocate shared expenses across operating units while preserving source transactions and reconciling unit-level results to company totals.
* **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** — At what maximum land acquisition price does this development project become a bankable investment? — Evaluate residential development opportunities by screening land comparables, estimating construction costs, and calculating profit-on-cost thresholds.
* **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — Will this construction project actually hit its target margin once site logistics, waste factors, and trade rate changes are accounted for? — Separate physical building quantities from volatile trade rates and site preliminaries to cascade commercial markups across tender budgets and client quotations.
* **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — Which wholesale prices and customer segments actually preserve margin once freight, duties, payment terms, and FX are fully costed? — Calculate SKU-level landed costs, cost-to-serve, and pocket-margin price waterfalls to simulate cross-border wholesale profitability.
* **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — What should we charge for a custom label order at each quantity tier to stay competitive and profitable? — Calculate parametric label pricing by modeling substrate square-inch costs, setup charges, and quantity-tier discount breaks against competitor benchmarks.
* **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — What is the true net margin on each SKU once actual landed costs and retailer deductions are accounted for? — Reconcile PO-estimated landed costs against actual freight, duty, FX, and drayage charges while auditing retailer remittance deductions to expose SKU-level net margin.
* **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — Can we make this week's hiring, marketing, and vendor commitments without running out of cash before the books close? — Track weekly cash burn pacing, MRR/ARR waterfall variance, retention metrics, and payroll costs against budget before month-end close.
* **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — Will our growth plan run out of cash before cohort monetization catches up? — Forecast multi-year cash burn, runway, unit economics, and fundraising dilution from bottom-up cohort and headcount assumptions.
* **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — Is each Shopify storefront actually profitable once true SKU-level costs, shared expenses, and bank charges are reconciled? — Reconcile multi-store Shopify sales exports against SKU-level COGS, allocated multi-currency OPEX, and bank statements to produce a trustworthy monthly P&L.
* **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — Which tour bookings actually generate net profit and positive cash flow after supplier costs and B2B collections? — Calculate per-booking tour job costs, gross margins, AR/AP settlement, and operating cash flow across multiple currencies.

See the GitHub profile and product collection for the broader toolkit series.

## License

This project is released under the **Apache License 2.0**.

See the repository license file for the complete terms and conditions.

