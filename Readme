# F1 Tyre Degradation & Pit Strategy Decision Intelligence

## Project Overview
This project builds an end-to-end **Formula 1 tyre degradation and pit strategy decision model** using real lap-level race data.

The objective is **not to predict race winners**, but to support **strategy decisions**, such as:
- Whether to pit or stay out  
- When a pit stop becomes beneficial  
- How tyre degradation compares to pit stop time loss  

The project demonstrates how raw motorsport data can be transformed into actionable decision intelligence using Python, Excel, and SQL-style analytics.

---

## Business Problem
In Formula 1, pit stop decisions involve a critical trade-off:

- Staying out leads to increasing lap times due to tyre degradation  
- Pitting provides fresh tyres but incurs significant time loss  

Poor strategy decisions can cost multiple race positions.  
This project quantifies that trade-off and evaluates strategy outcomes using real data.

---

## Data Sources (Real, Public Datasets)

### 1. FastF1 — Primary Performance Data
- **Source:** https://docs.fastf1.dev/
- **Type:** Official Formula 1 timing data accessed via Python library  
- **Used for:**
  - Lap times  
  - Tyre compounds  
  - Stint information  
  - Track status (green flag, safety car)  

Data is retrieved dynamically and is not stored in the repository due to size constraints.

---

### 2. ERGAST Formula 1 Dataset — Historical Data
- **Source:** https://ergast.com/mrd/
- **Access Method:** CSV files  
- **Used for:**
  - Pit stop timing data  
  - Historical race context  

**Key file used:**
- `pitstops.csv` — pit stop duration in milliseconds  

Both datasets are widely used in motorsport analytics and academic research.

---

## Tools & Technologies
- Python (pandas, NumPy, scikit-learn)
- Google Colab
- Excel (exploratory analysis and validation)
- SQL-style analytics (implemented using pandas)

---

## Methodology
1. Load real lap-level race data using FastF1  
2. Perform exploratory analysis in Excel to understand tyre behaviour  
3. Clean race laps by removing:
   - Pit in / pit out laps  
   - Safety car laps  
   - Inaccurate or deleted laps  
4. Engineer a `LapInStint` feature to model tyre wear  
5. Build linear regression models to estimate tyre degradation rates  
6. Load historical pit stop data and estimate average pit stop time loss  
7. Compare race strategies using total-time decision logic  

---

## Key Outputs
- Tyre degradation rate per compound (seconds per lap)  
- Base pace estimates on fresh tyres  
- Estimated pit stop time loss  
- Strategy comparison (No Pit vs One Pit)  

---

## Project Files
- `F1_Tyre_Degradation_EndToEnd.ipynb` – Full analysis and modelling notebook  
- `tyre_degradation_results.csv` – Tyre degradation model outputs  
- `strategy_comparison.csv` – Strategy evaluation results  
- `excel_tyres_exploration.xlsx` – Excel-based exploratory analysis  
- `requirements.txt` – Python dependencies  

---

## Final Summary
Built an end-to-end Formula 1 tyre degradation and pit strategy decision model using real lap-level data, Excel for exploratory analysis, Python for preprocessing and modelling, and SQL-style logic for pit stop cost estimation.

