# Machine Learning for Earth Systems Modeling

Welcome to the **MLEarthSystemsModelling** repository. 

This repository collects examples and notebooks developed for the "Machine Learning for Earth Systems Modeling" course. The main goal of this project is to apply Machine Learning techniques to improve weather forecasts by analyzing and correcting the errors of traditional physical models.

## Main Topics and Contents

Currently, the project focuses on using the **Random Forest** algorithm to estimate temperature forecast errors:

*   **Random Forests for Post-Processing**: Training Random Forest models to predict and correct the 2-meter temperature forecast error (2t_error).
*   **Variables Analysis**: Studying the relationships between the forecast error and key meteorological variables, such as time of day (time_of_day) and soil temperature (soil_temp).
*   **ECMWF Data**: Using and analyzing datasets from the European Centre for Medium-Range Weather Forecasts (ECMWF).

## Repository Structure

*   `1.2 - Random forests/`: Main folder containing the files related to the Random Forest model.
    *   `Postprocessing_Random_Forest.ipynb`: Jupyter Notebook containing the code for training, validation, and post-processing of the model.
    *   `figures/`: Graphs generated from the analysis (e.g., scatter plots of the error versus time of day and soil temperature).
    *   `object-store.os-api.cci1.ecmwf.int/sop/`: Contains the datasets used, including `forecast_error.csv`.
