# Costco Warehouse Expansion Analysis

[Download the Excel workbook](./Costco-Project.xlsx)

## Project summary

I worked with a team to develop an Excel framework for evaluating a proposed expansion of 10 company-owned Costco warehouses in the United States. Our starting scenario was a $500 million investment, with an estimated $50 million cost per warehouse and a 20-year operating period.

The main question was whether the expansion could generate enough incremental cash flow to justify the investment. That meant looking closely at how new warehouses reach mature sales, how membership fees contribute to revenue, and how much business might shift from existing Costco locations.

## My contribution

I developed the assumptions for the expansion by comparing them with the company data. I used that information to judge what was reasonable, explain the reasoning behind the assumptions, and recommend a base case for Costco.

I focused on how the assumptions fit the business: the time a new warehouse needs to reach mature sales, the investment required to open it, and the risk that some sales would come from existing locations. I wanted the recommended case to have a clear basis in the data and to make the uncertain inputs visible.

The WACC calculation and other workbook sections are included as part of the team deliverable. My contribution described here is the assumptions work.

## What the workbook contains

- **Project overview:** the proposed investment, evaluation period, value drivers, and major risks.
- **Company data and sources:** operating information, capital structure inputs, and source references used in the analysis.
- **Assumptions map:** base assumptions, derivations, supporting rationale, and ranges for future testing.
- **WACC calculation:** CAPM-based cost of equity, cost of debt, effective tax rate, and debt/equity weights.
- **Summary and open questions:** the weakest assumptions and decisions still needed to complete the valuation.
- **Cash flow treatment:** planned treatment of initial investment, operating cash flow, working capital, terminal value, and financing costs.

## Key calculations and assumptions

These are inputs and results recorded in the submitted workbook, rather than independently verified current market data.

| Item | Workbook value | Meaning |
| --- | --- | --- |
| Proposed initial investment | $500 million | 10 warehouses at $50 million each |
| Evaluation period | 20 operating years | Year 0 is the initial investment period |
| Mature annual merchandise sales | $292 million per warehouse | Target for Year 5 |
| First-year sales | Approximately 64% of target | Starting point for the sales ramp |
| Sales cannibalization | 10% | Assumed sales transferred from existing warehouses |
| Operating margin | Approximately 3.48% | U.S. segment margin applied to sales plus membership fees |
| Cost of equity | 9.57% | Risk-free rate + beta × equity risk premium |
| Pre-tax cost of debt | 5.76% | Risk-free rate plus AA credit spread |
| WACC | Approximately 9.50% | Equity cost plus after-tax debt cost, weighted by capital structure |

The WACC calculation uses a 5.22% risk-free rate, a beta of 0.87, and a 5.00% equity risk premium. The workbook links the calculation back to its data sheet so the inputs can be traced.

## My takeaway

I think the most important part of this project is the discipline behind the assumptions. A new warehouse can report strong sales while still adding less value than expected if it takes customers from an existing location or costs more to build. I want the investment case to show that clearly.

The workbook also explains why interest expense should be excluded from unlevered project cash flow: financing costs are already represented in WACC. Keeping that treatment consistent matters when evaluating the investment.

## Status and next steps

This deliverable is the foundation for a valuation. The submitted workbook does **not** contain a completed 20-year cash flow schedule, NPV, IRR, or executed sensitivity analysis.

The next steps identified in the workbook are to complete the cash flow forecast, resolve depreciation and terminal-value assumptions, validate working capital requirements, and test construction cost, cannibalization, revenue growth, project life, and WACC.

## Team credit

The original workbook credits Justin Pop, Jake Hiu, Sulo Mecaj, and Juan Dominguez. My contribution was developing and supporting the assumptions and recommending the base case. The full workbook represents the team's combined work.
