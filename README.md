The project represents a Discounted Cash Flow (DCF) valuation of NVIDIA Corporation (NVDA) which is used to estimate the intrinsic equity value and implied share price of the company.

The model forecasts NVIDIA's future free cash flows (FCF) based on historical financial performance and key operating assumptions, discounts these cash flows using the Weighted Average Cost of Capital (WACC), and calculates an implied enterprise value, equity value, and share price.

Objectives:
Build a five-year DCF valuation model
Forecast revenue, EBIT, and operating margins
Estimate EBIAT and unlevered free cash flow
Calculate WACC and terminal value
Derive enterprise value and equity value
Calculate NVIDIA's implied share price
Compare the DCF valuation with the company's market price


The valuation follows the standard DCF framework:

Revenue → EBIT → EBIAT → Unlevered Free Cash Flow → Present FCF Value → Terminal Value → Present Terminal Value → Enterprise Value → Equity Value → Implied Share Price

Unlevered Free Cash Flow is calculated as:
UFCF = EBIT × (1 − Tax Rate) + D&A − CapEx − Change in NWC

Present FCF is calculated as:
PFCF = UFCFₙ/(1+WACC)^n

The terminal value is calculated using the perpetuity growth method:
Terminal Value = UFCF × (1 + tgr) / (WACC − tgr)

Enterprise Value is calculated by discounting projected free cash flows and the terminal value to present value.

Equity value is then calculated as:
Equity Value = Enterprise Value + Cash & Marketable Securities − Debt

Finally:
Implied Share Price = Equity Value / Shares Outstanding
