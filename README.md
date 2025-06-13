# Ferry-Ticket-Prediction

## Project Overview

This repository contains two independent Jupyter notebooks for forecasting tasks related to ferry ticket operations:

- **Redemption_model.ipynb** – Forecasts ticket redemptions.
- **Sales_model.ipynb** – Forecasts ticket sales count.

The project also includes:
- A summary report
- Required data files
- A configuration file (`config`) for model parameters

---

## Repository Structure

```
Ferry-Ticket-Prediction/
│
├── data/                   # Folder containing required data files
├── config/                 # Folder containing the configuration file
├── Redemption_model.ipynb  # Notebook for redemption prediction
├── Sales_model.ipynb       # Notebook for sales forecasting
└── README.md               # Project description and instructions
```

---

## Notebook Structure

Each notebook is self-contained and follows this structure:

1. **Library Imports**  
   - Lists all required libraries at the top.  
   - Ensure all libraries are installed before running the notebooks.

2. **Custom Classes and Functions**  
   - Includes helper functions and class definitions used in model development and evaluation.

3. **Execution Cell**  
   - The final cell executes the model using logic and parameters defined in previous sections.

---

## Configuration & Data

- Both notebooks rely on a shared **configuration file** and a **data file**.
- These should be located in the same directory.
- Model parameters are primarily loaded from the config file.
- Default values are provided in the notebooks to serve as fallbacks if configuration entries are missing.

Thanks
---

