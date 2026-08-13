# Promotion Strategy Selection for Perishable Clearance
**A Threshold-Based Analysis of the Profit–Waste Trade-off**

This repository contains the Python simulation code (Jupyter Notebooks) for the MSc Management (Supply Chain Logistics) dissertation.

## Project Overview
This project investigates the operational trade-off between maximising profitability and mitigating food waste during grocery clearance sales. By utilising a fluid approximation and Monte Carlo simulations, the model evaluates three discrete promotion strategies:
* Standard Price Discount
* Bundle Pricing
* Buy-One-Get-One-Free (BOGO)

The code identifies the Threshold-based Promotion Policy (TPP) under demand uncertainty, capturing continuous physical deterioration and non-linear consumer behavioural expansion.

## Repository Structure
* `src/` : Contains all Jupyter Notebooks for numerical simulations and sensitivity analysis.
  * `Figure_2_Strategy_Performance_under_Varying_Waste_Penalty_(λ).ipynb` : Evaluates performance under varying waste penalties.
  * `Figure_3_Strategy_Performance_under_Varying_Discount_Depth_(d).ipynb` : Analyses the impact of discount depth.
  * `Figure_4_Strategy_Performance_under_Varying_Bundle_Pricing_Factors_(α).ipynb` : Analyses bundle pricing factor boundaries.
  * `Figure_5_Strategy_Performance_under_Varying_Inventory_Levels_(Q).ipynb` : Evaluates capacity stress-tests (Newsvendor logic).
  * `Figure_6_Strategy_Performance_under_Varying_Perishability_Levels.ipynb` : Evaluates performance across physical decay rates.
    * `Figure_6.1_Conceptual_Illustration_of_Stochastic_Threshold_Drift.ipynb` : Visualises the Stochastic Threshold Compression Effect.
  * `Figure_7_Strategy_Performance_under_Stochastic_Demand.ipynb` : Evaluates the impact of consumer behavioural demand expansion and numerically validates the psychological threshold.
  * `Table3_and_Table4.ipynb` : Contains scripts generating the numerical sensitivity grids.
* `figures/` : Contains the output visualisation plots used in the dissertation.
* `requirements.txt` : Lists all necessary Python dependencies.

## How to Run
1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
4. Navigate to the `src/` folder, open any of the `.ipynb` files, and click "Run All" cells to reproduce the simulations and figures. Alternatively, you can upload the notebooks to Google Colab for execution.

