# GQV Analyzer  

**GQV Analyzer** is a stock analysis tool designed to streamline decision-making for investors by aggregating and visualizing critical metrics under three categories: Growth (G), Quality (Q), and Valuation (V). This framework provides a quantitative foundation for evaluating stocks, enabling users to identify investment opportunities with strong fundamentals.  

---

## Features  

### Metric Categorization  
- **Growth (G):** Tracks historical and projected growth rates, such as revenue growth, EPS change, and CAGR.  
- **Quality (Q):** Measures operational stability, including cash flow growth, debt ratios, and profitability.  
- **Valuation (V):** Compares valuation metrics like P/E ratio, EV/EBITDA, and PEG.  

### Custom Scoring  
- Calculates average scores for each metric group (G, Q, V) and combines them into an overall GQV score.  

### 3D Visualization  
- Displays GQV scores in an interactive 3D plot, with axes representing Growth, Quality, and Valuation.  
- Includes minimum and maximum data points to normalize the visualization for easier interpretation.  

### Comprehensive Stock Screening  
- Includes functionality for downloading stock data and calculating key metrics like Compound Annual Growth Rates (CAGR).  

---

## How It Works  

### Data Aggregation  
- Collects data from reliable financial APIs for metrics like revenue growth, EPS, and valuation ratios.  

### GQV Calculation  
- Categorizes metrics into groups (G, Q, V) based on predefined dictionaries.  
- Averages scores within each group and combines them into an overall GQV metric.  

### Visualization  
- Plots the GQV metrics on a 3D scatter plot, enabling users to identify outliers, clusters, or balanced opportunities.  

---

## Example Use Case  

**Objective:** Identify balanced stocks with strong growth, stable operations, and fair valuation.  
**Input:** A list of stock tickers.  
**Output:**  
- Individual G, Q, V scores.  
- 3D visualization of stocks with interactive exploration.  

### Interpretation  
- Stocks closer to (1,1,1) are ideal, as they balance growth, quality, and valuation metrics.  
- Outliers may represent undervalued opportunities or risky bets.  

---

## Notes on Interpretation  
- Negative values in GQV metrics are possible and indicate specific risks (e.g., declining revenues, high debt).  
- Scores are relative to the dataset and should be interpreted in the context of market conditions.  
