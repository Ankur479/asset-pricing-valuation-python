**Overview**
This project aims to analyze the intrinsic value of a company (Apple Inc.) using the Discounted Cash Flow (DCF) method and compare it with the market price. It also examines how Beta (systematic risk) and the expected return (CAPM model) are related to the valuation results.
**Objectives**
To calculate Beta using historical stock and market data
To estimate the Expected Return using the CAPM model
To perform a DCF valuation to find the Intrinsic Value per Share
To compare the Intrinsic Value vs Market Price and visualize the difference
**Key Concepts**
Beta (β) → Measures stock’s volatility compared to the market
CAPM (Expected Return) → E(R) = Rf + β * (Rm - Rf)
Free Cash Flow (FCF) → Real cash generated after all expenses
DCF Valuation → Present value of all projected FCF + terminal value
Intrinsic Value → True estimated worth of the stock based on cash flows
**Tools & Libraries Used**
Python
pandas, numpy
matplotlib
yfinance
**Methodology**
Data Extraction: Downloaded Apple and S&P500 historical data using yfinance
Beta Calculation: Computed covariance and variance to derive Beta
Expected Return: Used CAPM model
DCF Valuation: Projected free cash flows, applied discount rate and terminal value
Visualization: Compared intrinsic and market prices using annotated bar chart
**Results Summary**
Parameter	Result
Calculated Beta	1.20
Expected Annual Return (CAPM)	11.18%
DCF Value Estimate (Intrinsic)	$108 per share
Market Price (Actual)	$279 per share
**Interpretation:**
The market price of Apple stock is significantly higher than its intrinsic value, indicating investor optimism and expectations of future innovation and growth.


datetime
