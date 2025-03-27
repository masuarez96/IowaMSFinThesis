# Restaurant Financial Similarity & PECOTA-Inspired Projection Model

This notebook combines restaurant financial analysis with a PECOTA-style projection system to evaluate and forecast the potential success of young or emerging restaurant businesses. Originally developed as part of a master's thesis project in finance and economics, the model uses historical financial data and similarity scoring to identify comparable businesses and predict future outcomes.

## Project Highlights

- **Similarity Scoring**: Uses key financial ratios (e.g., Gross Margin, Net Income Margin, Revenue Growth) to match young restaurants with more established counterparts.
- **PECOTA-Style Forecasting**: Inspired by the baseball projection model PECOTA, this approach blends similarity scores and peer performance to build robust financial forecasts.
- **Custom Data Pipeline**: Parses and cleans raw financials, generates comparison metrics, and produces clear tables for analysis.
- **Exploratory Data Analysis**: Includes visualizations and correlation metrics to better understand which financial factors are most tied to success.

## Objectives

- Identify which financial attributes are most predictive of long-term restaurant success.
- Help investors and analysts evaluate new or private restaurant businesses by comparing them to established peers.
- Experiment with a hybrid model blending quantitative finance with behavioral economics and sports analytics.

## Contents

- `RestaurantSimilarityandPECOTAModel.ipynb`: Main analysis and modeling notebook.
- Functions for:
  - Data ingestion and cleaning
  - Ratio calculation
  - Similarity scoring using Euclidean distance and percentile matching
  - Forecast generation
- Tables and visual outputs showing:
  - Closest financial "neighbors"
  - PECOTA-style projections
  - Statistical summaries

## Tools & Libraries

- `pandas`: data manipulation and transformation  
- `numpy`: numerical computation  
- `matplotlib.pyplot`: plotting and data visualization  
- `scipy.spatial.distance`: similarity scoring via Euclidean distance  
- `IPython.display`: notebook-based output formatting  

## Use Case

This project is especially relevant for:
- Financial analysts exploring private or early-stage company performance
- Venture capitalists assessing new restaurant ventures
- Researchers interested in applying sports-style analytics to finance
- Data scientists blending interpretability with forecasting

## Future Directions

- Integrate machine learning models (e.g., k-NN, random forest) for automated similarity selection
- Expand data sources to include market trends and sentiment analysis
- Explore time-series forecasting for multi-year projections
- Build a dashboard interface for business users

## Contact

For questions, feedback, or to connect professionally, visit my [LinkedIn](https://www.linkedin.com/in/michael-suarez-10989a172).
