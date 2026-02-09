# Econ-Agent Market Simulator

A multi-agent simulation environment where autonomous agents trade resources within a closed economy. This project explores emergent market behaviors and price discovery mechanisms using reinforcement learning principles.

## Project Overview
The simulation models a scarcity-based economy where agents must acquire resources (Food, Wood, Stone) to "survive" or maximize a utility function.

### Key Features
* **Agent Decision Making:** Agents use utility functions to determine the marginal value of goods based on current inventory.
* **Market Mechanism:** A double auction system where agents submit bids and asks, clearing at an equilibrium price.
* **Macro-Analysis:** Tracks inflation, trade volume, and wealth inequality (Gini coefficient) over time.

## Tech Stack
* **Language:** Python 3.11+
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib/Seaborn for real-time price charting.
