# Machine Learning-Based Web Application for Predicting Malaria Prevalence Using Satellite Imagery

## Overview

This repository contains the source code developed for the study:

"Machine Learning-Based Web Application for Predicting Malaria Prevalence
Using Satellite Imagery: A Case Study of Karagwe District, Tanzania."

The study integrates satellite-derived environmental variables and machine
learning to estimate Plasmodium falciparum parasite prevalence among children
aged 2–10 years (PfPR2–10) in Karagwe District, Tanzania.

## Study Period

2020–2024

## Study Area

Karagwe District, Kagera Region, Tanzania.

## Data Sources

The study uses data from:

- Sentinel-2
- MODIS MOD11A1
- CHIRPS
- SRTM DEM
- JRC Global Surface Water
- Malaria Atlas Project (MAP)

## Environmental Variables

The environmental predictors include:

- NDVI
- NDWI
- NDMI
- MNDWI
- NDBI
- Rainfall
- Land Surface Temperature
- Elevation
- Slope
- Distance to Water

## Machine Learning

The repository contains implementations of:

- Random Forest Regression
- XGBoost
- Spatial cross-validation
- Feature importance analysis
- Model evaluation using R², RMSE and MAE

## Web Application

The Streamlit application provides:

- Prediction year selection
- AOI upload
- PfPR2–10 prediction
- Interactive map visualisation
- Environmental variable visualisation
- GeoTIFF download
- GeoJSON download

## Repository Structure

GEE/
    Google Earth Engine scripts

Google_Colab/
    Machine learning and data processing code

Streamlit/
    Web application source code

Model/
    Model configuration files

Data/
    The data used in this study is public available data
