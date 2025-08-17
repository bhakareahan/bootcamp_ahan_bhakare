

# Project Title

Investigating HFT strategies on the S&P 500 index



**Stage**: Problem Framing & Scoping (Stage 01)



## Problem Statement



The S&P 500 is one of the most liquid indices in the world. However, because of the high-liquidity, creating high frequency strategies to exploit any potential mispricing can be very difficult due to slippage and cumulative trading costs. The purpose of this analysis is to run through some basic technical indicators (Moving Averages) and some quantitative metrics (VIX daily volatility) to try to discover any potential trading ideas.



The primary stakeholder is the managing fund; end users are the traders that will monitor the trading idea and its functionality. 



### Stakeholder & User

**Decision owner**: The decision owner is the PM that is managing the fund that wants this problem explored/solved.

**Tool/operator**: Traders who will actively monitor the algorithm and its functionality.



### Useful Answer

**Descriptive / Predictive / Causal**: Descriptive/Predictive

**Metric or artifact**: Will use technical indicators, like MA and EMA, and quantitative intervals, like daily volatility bands, to assess PnL.



### Assumptions & Constraints

- Market data relating to the S&P and VIX are continuous and available since it is a very liquid and highly watched index. 

- For higher frequencies, we assume that we will have 15-minute interval data.

- Constraints include slippage costs as they are unknown at this time, so we will assume a 0.3% slippage cost to accommodate this pitfall.



### Known Unknowns / Risks

- **Known**: Slippage is present within these high frequency trades (hence why there is an assumed slippage cost added). Additionally, bid-ask prices are not exactly known, so spread might larger at certain points. To counter this, we include that slippage to create the illusion of a bid and ask being present.

- **Unknown**: Major news events that won't be accounted in these models as they do not have the capability to analyze this component. 



### Lifecycle Mapping

- Goal → Stage → Deliverable mapping bullets



- Frame the problem that I want to solve and understand how to go about gathering all of the relevant details → Problem Framing & Scoping (Stage 01) → Scoping Paragraph + README.md

### Repo Plan
/data/, /src/, /notebooks/, /docs/ ; updates weekly to understand the progress the strategies make.