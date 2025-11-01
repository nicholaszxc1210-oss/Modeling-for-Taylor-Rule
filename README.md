README — Pressure-Adjusted Taylor Rule Simulation
Overview

This repository contains an implementation of the pressure-adjusted Taylor rule, inspired by Sections 3–5 of Pioneer Academics Final (2025).
It models how political pressure can distort central bank policy from its rule-based benchmark, and quantifies the resulting effects on inflation, output, and welfare.

The model includes three country-style scenarios — United States, India, and Turkey — with calibrated pressure magnitudes reflecting different levels of political influence.
Simulates a toy New-Keynesian environment for inflation (π) and output gap (y).

Calibrates the pressure coefficient 
𝜅
κ to reproduce qualitative “influence shares”:

United States: ≈ 55%

India: ≈ 40%

Turkey: ≈ 95%

Produces figures for each scenario and exports all series to CSV.

It will:

Simulate 100 periods for each country case

Generate CSVs and figures in the current folder

Print calibrated κ-values and discounted welfare metrics
Interpretation

κ (kappa) reflects the degree to which political pressure translates into rate deviations.

Discounted welfare loss captures both macroeconomic instability and the distortionary cost of political interference.

Cross-country comparisons illustrate how stronger or more sustained pressure (Turkey) leads to larger deviations but not necessarily lower welfare, depending on parameters.
License

MIT License — you are free to use, adapt, and cite with attribution.
