# ComfortDelGro (SGX: C52) - Equity Valuation Model

## Project Overview
This repository contains a fully integrated, three-statement financial model and equity valuation for **ComfortDelGro Corporation Limited (SGX: C52)**, one of the world’s largest land transport companies. 

The objective of this project was to determine the intrinsic per-share value of the core operating business using a Discounted Cash Flow (DCF) framework, cross-referenced with a global Comparable Company Analysis (Comps).

## Technical Architecture & Modeling Features
* **Integrated 3-Statement Core:** Built from raw annual filings, featuring dynamically balancing income statements, balance sheets, and cash flow statements with zero circularity errors.
* **Complex Roll-Forwards:** Automated schedules for Debt (differentiating short/long-term and lease liabilities), Property, Plant & Equipment (PP&E), and Retained Earnings.
* **Strict Cash Flow Isolation:** Unlevered Free Cash Flow (UFCF) is rigorously derived by isolating Net Operating Profit After Taxes (NOPAT) and adjusting strictly for *Operating* Net Working Capital (stripping out cash and financing liabilities).

## Valuation Methodology & Assumptions
The valuation triangulates ComfortDelGro's intrinsic value using both intrinsic and relative methodologies.

### 1. Discounted Cash Flow (DCF)
* **WACC Calibration (3.19%):** Localized to the Singapore macroeconomic environment using the 10-Year SGS yield as the risk-free rate, adjusted for a localized Equity Risk Premium and a blended pre-tax cost of debt.
* **Dual-Method Terminal Value:**
  * *Perpetuity Growth Method:* Assumes a highly defensible **2.0%** long-term macroeconomic growth rate.
  * *Exit Multiple Method:* Applies a **3.96x** EV/EBITDA multiple to terminal year earnings.
* **Enterprise to Equity Bridge:** Fully adjusted for cash equivalents, total debt (including IFRS 16 leases), and minority interests.

### 2. Comparable Company Analysis (Comps)
Screened a global peer group of land and marine transport operators to benchmark the Exit Multiple. 
* **Peer Group:** Kelsian Group (ASX: KLS), FirstGroup (LSE: FGP), and Mobico Group (LSE: MCG).
* **Analytical Adjustments:** Corrected UK listing currency conventions (GBp to GBP) to prevent market cap distortion, and adjusted the peer median to account for distressed European leverage profiles versus stable APAC transit contracts.

## Conclusion & Price Target
* **Implied Intrinsic Value:** **$1.14 SGD**
* **Current Market Price:** ~$1.45 SGD
* **Analyst Thesis:** Under baseline operating assumptions, the pure unlevered cash flows (discounted at 3.19%) yield an intrinsic value of $1.14. This suggests the current market premium is actively pricing in aggressive margin recovery or a higher volume of overseas transit tender wins.

---
*Disclaimer: This model was built for educational and portfolio demonstration purposes. It does not constitute professional investment advice.*
