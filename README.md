# New Zealand Treasury Fiscal Strategy Model (FSM) Baseline Replicator

A quantitative simulation engine built in Python to replicate the NZ Treasury's Fiscal Strategy Model (FSM), projecting the Operating Balance Before Gains and Losses (OBEGAL), Net Core Crown Debt, and macroeconomic shock vulnerabilities over a 10-year horizon.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/1jpU-ZqRKOB8-8sC-6SHKojscglkYTscu?usp=sharing])

---

## Public Policy Problem & Context
The Treasury Te Tai Ōhanga is responsible for advising the New Zealand Government on fiscal strategy, debt sustainability, and medium-term spending choices. 

Evaluating new budget spending solely on immediate cash impacts obscures the long-term structural deficit once compounding debt servicing and dynamic revenue elasticities are accounted for. This tool simulates the complete fiscal trajectory under varying macroeconomic conditions to help policy teams evaluate the impact of operating allowances, optimize paths to an OBEGAL surplus, and ensure debt remains below the government's target limits.

---

## Key Features & Analytics

- **Dynamic Tax Revenue Modeling:** Automatically calculates core Crown tax revenue based on nominal GDP growth expectations and assumed tax buoyancies.
- **Cumulative Operating Allowances:** Integrates discretionary new budget spending packages and compounds them across the 10-year forecast horizon.
- **Net Core Crown Debt Accumulation:** Calculates ongoing debt servicing costs via effective interest rate transmission and tracks Net Debt against the Crown's 40% target ceiling.
- **Stochastic Shock Testing:** Runs Monte Carlo simulations (1,000 iterations) applying randomized GDP growth shocks to bound the uncertainty of future debt trajectories.
- **Policy Pathway Evaluation:** Automatically evaluates fiscal scenarios and identifies the specific fiscal year the OBEGAL balance successfully returns to a structural surplus.

---

## Visualizations

### 1. OBEGAL Trajectories & Operating Allowance Scenarios
<img width="1492" height="525" alt="obegal_scenarios" src="https://github.com/user-attachments/assets/1b90b255-7413-4a14-b80c-2b5068c4155f" />


### 2. Net Core Crown Debt vs. Target Ceiling
<img width="1492" height="525" alt="debt_trajectory" src="https://github.com/user-attachments/assets/13c768ec-140d-4ebc-8f6e-69856d2dd636" />


### 3. Stochastic Debt Sustainability Analysis (S-DSA)
<img width="1492" height="525" alt="monte_carlo_fan_chart" src="https://github.com/user-attachments/assets/c1f3508f-b0b8-4f96-8fef-46236153d126" />


---

## Tech Stack
- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Statistical Modeling:** SciPy (Monte Carlo Simulations)
- **Data Visualization:** Plotly Graph Objects, Plotly Express

---

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/ankushgulati2121-bit/NZ-Treasury-Fiscal-Strategy-Model.git](https://github.com/ankushgulati2121-bit/NZ-Treasury-Fiscal-Strategy-Model.git)
