# HR_Framework
HR framework for token equity distribution for employee scenarios

# Token Allocation Simulation

This repository contains a Python script to simulate token allocation and depletion across different project phases, taking into account the number of employees, risk coefficients, and various contextual factors.

## Features

- **Dynamic Adjustment:** Adjusts the number of employees across phases based on total headcount.
- **Risk Coefficients:** Applies phase-specific risk coefficients to reflect the uncertainty of each stage.
- **Customizable Parameters:** Includes Salary Level (SL), Role Importance (RI), and Salary Category (SC) as adjustable coefficients for each phase.
- **Scenario Comparison:** Simulates token depletion for various employee counts and total token allocations.
- **Visualization:** Provides a comparative plot of token depletion over time.

## Requirements

The script requires the following Python libraries:
- `pandas`
- `matplotlib`

Install the required dependencies with:
```bash
pip install pandas matplotlib
