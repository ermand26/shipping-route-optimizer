# Physical Shipping & Freight Route Optimizer

A lightweight data engineering project that analyzes physical ocean trade routes by integrating macro commodity fuel inputs to discover the lowest-cost logistical transit paths.

##  Core Analytical Features
* **Live Market Indicators:** Dynamically handles live endpoints to model bunker fuel price variances.
* **Multi-Route Matrix Modeling:** Runs continuous trade-off equations between distances, canal tolls, and temporal vessel hire costs.
* **Automated Decision Engine:** Generates a structured DataFrame ranking routes from lowest to highest total operational cost.

##  Step-by-Step Installation Guide

Follow these simple commands inside your terminal to run the optimization framework:

1. **Clone the newly created project repository:**
   ```bash
   git clone https://github.com
   cd shipping-route-optimizer
   ```

2. **Establish a clean project virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the required analytic packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute the optimization pipeline script:**
   ```bash
   python optimizer.py
   ```
