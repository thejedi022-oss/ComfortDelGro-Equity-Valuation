# ComfortDelGro Equity Valuation

This project is a self-built equity valuation model for **ComfortDelGro Corporation Limited**, developed to strengthen my financial modelling, valuation, and investment analysis skills.

I built the model independently after learning financial modelling through self-study and online resources. At the start of the project, I had limited Excel modelling experience, so a significant part of the work involved learning how to structure and link a complete valuation model from the ground up.

## Model Overview

The workbook includes:

- Historical and forecast **Income Statement**
- **Balance Sheet** forecasting
- **Cash Flow Statement**
- **Fixed Asset Schedule**
- **Debt Schedule**
- **Retained Earnings Schedule**
- **Non-Controlling Interest Schedule**
- **Beta estimation**
- **WACC calculation**
- **Comparable Company Analysis**
- **Unlevered Free Cash Flow DCF**
- **Perpetuity Growth Terminal Value**
- **Exit Multiple cross-check**
- **WACC / Terminal Growth sensitivity analysis**
- Base, best-case, and worst-case operating assumptions

## Valuation Approach

The primary valuation method used is a **Discounted Cash Flow valuation based on Unlevered Free Cash Flow**.

The model forecasts operating performance from historical financial data and estimates enterprise value using:

1. Present value of forecast free cash flows
2. Terminal value using the Gordon Growth Method
3. Enterprise-to-equity value bridge
4. Diluted shares outstanding to derive implied value per share

The exit multiple method is retained as a secondary valuation cross-check.

## Beta and WACC

Rather than relying solely on a third-party reported beta, I constructed a beta estimate using comparable companies.

Peer betas were unlevered using their respective capital structures, averaged to estimate industry operating risk, and then relevered using ComfortDelGro's capital structure.

The resulting WACC is approximately **4.2%**, which is used to discount forecast cash flows and terminal value.

## Sensitivity Analysis

Because terminal value represents a significant portion of total enterprise value, the model includes a two-variable sensitivity analysis across:

- **WACC**
- **Perpetual growth rate**

The base-case assumptions are approximately:

- WACC: **4.2%**
- Terminal growth: **2.0%**

These assumptions produce an implied equity value of approximately **SGD 1.81 per share**.

## Key Learning Outcomes

This project helped me develop practical experience in:

- Building integrated financial models from raw financial statements
- Linking the three financial statements
- Forecasting operating performance
- Understanding working capital and cash flow drivers
- Constructing supporting schedules
- Estimating beta and cost of capital
- Performing DCF valuation
- Building sensitivity analysis
- Auditing financial models for formula and linking errors
- Distinguishing between model structure, assumptions, and valuation judgment

One of the biggest lessons from the project was that financial modelling is not only about constructing formulas. A significant part of the process involves ensuring that assumptions, financial statements, supporting schedules, and valuation outputs remain internally consistent.

## Project Context

The model was completed independently in approximately one month while balancing university studies and CFA-related study.

Rather than using a pre-built reference model, I adapted financial modelling concepts from educational material to ComfortDelGro's publicly available financial information and developed the forecasting assumptions and valuation structure myself.

## Disclaimer

This model was created for educational and portfolio purposes only.

It does not constitute investment advice, and the assumptions and valuation outputs should not be interpreted as a recommendation to buy or sell ComfortDelGro securities.
