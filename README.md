#  Techno-Economic Analysis (TEA) of Green Methanol Production

##  Project Overview
This repository contains a dynamic, Python-based simulation model for evaluating the Techno-Economic Analysis (TEA) of a green methanol production plant. The model is built to validate, audit, and expand upon existing academic literature using standard chemical engineering methodologies.

##  Key Features & Achievements
* **CAPEX Calculation:** Automated estimation of Fixed Capital Investment (FCI) and Total Capital Investment (TCI) using the factorial method (based on Towler & Sinnott standards).
* **OPEX Validation & Assumption Auditing:** Successfully reverse-engineered and validated literature operating costs, uncovering hidden depreciation parameters to achieve **< 1% error** in Variable and Fixed Operating Costs.
* **Financial KPIs:** Calculation of Cash Flow, Payback Period, and Levelized Cost of Product (LCOP).

##  Built With
* **Python** (Core computational engine)
* **Pandas** (Data extraction from Excel databases and data manipulation)
* **NumPy** (Iterative financial loops and mathematical modeling)

##  Current Status
* **Phase 1 (Completed):** Core OPEX/CAPEX engine validation.
* **Phase 2 (In Progress):** Dynamic sensitivity analysis (LCOP vs. Electricity/Capital costs) and data visualization.
