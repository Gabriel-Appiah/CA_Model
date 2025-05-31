# Modeling Wildfire Spread in California with Cellular Automata
Team 4: Gabriel Appiah, Katherine Losada, Kshitij Sawant, and Thanawit
Suwannikom
GitHub Repo: https://github.gatech.edu/tsuwannikom3/cse6730-project

This project develops a GIS-driven cellular automata framework to simulate wildfire spread
across a California case study using empirical land-use and fuel data. We discretize the study
area into grid cells classified as one of four states: no fuel, unburned fuel, burning, and burned
completely. State transitions occur in discrete time steps based on probabilistic functions
informed by (1) land-cover classes derived from California land-use data, (2) vegetation type and
density from satellite-derived NDVI rasters, (3) dynamic wind fields, and (4) terrain elevation.
Ignition probabilities follow a logistic-regression model calibrated with historical fire
occurrences and human-activity indicators. By replacing synthetic inputs with real-world
datasets, the simulation more accurately captures the complex dynamics of environmental drivers
and wildfire behavior. This framework provides emergency responders and environmental
agencies with a robust tool for understanding and forecasting fire behavior, supporting informed
decision-making during wildfire events.
