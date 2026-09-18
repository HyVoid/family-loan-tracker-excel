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

* **Business Decision Toolkits** — reusable Excel-based frameworks for recurring operational and financial questions.
* **Financial Planning & Reconciliation Tools** — focused models for turning raw records into decision-ready financial information.
* **Construction & Operations Toolkits** — practical workbooks for estimating, costing, planning, and operational control.

See the GitHub profile and product collection for the broader toolkit series.

## License

This project is released under the **Apache License 2.0**.

See the repository license file for the complete terms and conditions.

