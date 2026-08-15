# Hi, I'm Sanjida

**Industrial & Systems Engineer (M.S., University of Washington)** focused on operations research, simulation, and data science. I build models of physical systems — production lines, logistics networks, inventory policies — and use them to find constraints, size resources, and quantify what each decision costs.

Seattle, WA · 🔗 [LinkedIn](https://linkedin.com/in/sanjida-nasreen) · 📄 [Google Scholar](https://scholar.google.com/citations?user=E_aWgCYAAAAJ)

---

## Technical Skills

**Languages** Python · R · MATLAB · SQL
**Optimization** Gurobi · Linear / Integer / Mixed-Integer Programming · Network Optimization · Markov Decision Processes
**Simulation** SimPy · Siemens Tecnomatix Plant Simulation · Digital Twin Modeling
**Analytics** pandas · NumPy · scikit-learn · TensorFlow · Statistical Analysis · DOE / SPC
**Tools** Jupyter · Git · Minitab · SolidWorks

---

## Featured Projects

### [Multi-Line Production System Balancing](https://github.com/sanjida-nasreen/Production-line-balancing-simulation) · `Python` `SimPy`
Discrete-event simulation of a two-line, four-component assembly system. Diagnosed three
workstations saturated near 100% utilization while final assembly sat starved at 8.8%,
then rebalanced work content, retimed material release to bill-of-material ratios, and
resized transport batches.

**Result:** throughput up 7.5× (33 → 252 units), average wait at the primary bottleneck
cut from ~23 hours to under 10 seconds, and the line moved from a net operating loss to
a profit — validated over 10 independent replications.

### [Digital Twin for Manufacturing Decision Support](https://github.com/sanjida-nasreen/digital-twin-manufacturing-decision-support) · `Siemens Tecnomatix` `Python` `Bayesian Optimization`
Calibrated a digital twin of an assembly–inspection–rework–shipping line against 360 months of production data, then used Bayesian optimization with a Gaussian process surrogate to search six operating decisions under a $300K/month capital budget.

**Result:** predictive accuracy improved from R² = −7.0 to R² = 0.96. Validated the recommended configuration over 30 replications and traced the remaining 22% model-to-reality gap to training-data extrapolation rather than model misspecification.

### [Warehouse-to-Port Logistics Network Optimization](https://github.com/sanjida-nasreen/supply-chain-logistics-optimization) · `Gurobi` `Python`
Mixed-integer program trading off transportation, warehouse operating, and unmet-demand costs subject to capacity and fulfillment constraints.

**Result:** Optimized shipment allocation under warehouse capacity constraints while reducing total logistics cost by 5.6% and identifying capacity bottlenecks across the network.

### [Stockout Risk Forecasting](#) · `Python` `scikit-learn` `TensorFlow`
Classification framework on a 73,000-row, four-region retail time series with engineered rolling-demand features. Benchmarked Logistic Regression, Decision Tree, Random Forest, and LSTM under expanding-window cross-validation.

**Result:** F1 ≈ 0.97 for stockout risk classification.

### [Optimal Spaced Repetition via Markov Decision Processes](#) · `Python`
Stochastic shortest-path MDP for adaptive review scheduling, solved by value iteration. Compared the optimal policy against interpretable threshold policies to quantify the cost of simplicity.

---

## Publications

Four peer-reviewed IEEE papers on statistical estimation, sensing, and measurement — IEEE RA-L (2021), IEEE SMC (2020), IEEE/ASME AIM (2020), ICMIME (2017). [Google Scholar →](https://scholar.google.com/citations?user=E_aWgCYAAAAJ)

---

## Interests

Operations research · manufacturing systems · supply chain analytics · digital twins · decision analytics under uncertainty

Reach me on [LinkedIn](https://linkedin.com/in/sanjida-nasreen).
