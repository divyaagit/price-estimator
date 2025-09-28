# price-estimator

Key Points

-The CSV is monthly natural gas prices from Oct 2020 → Sep 2024.
-Interpolation converts monthly → daily for precise date queries.
-Forecast predicts future prices for 12 months using Holt-Winters method.
-Query function allows any date within historical + forecast.
-Visualization shows historical, interpolated, and forecast together.
