Merged 4 sources: Lending Club loans + NASA POWER rainfall + MODIS NDVI + SoilGrids soil data
Filtered farmer records via emp_title keyword; geocoded addr_state → lat/lon
Added drought flag (NDVI < 0.2), rainfall deviation, soil quality score
XGBoost AUC: 0.64, F1-score: 0.42
SHAP: rainfall and NDVI drought flag contributed most to defaults
Useful for microfinance risk teams targeting rural borrowers
