# IMU Human Activity Analysis

This project analyzes smartphone IMU data (accelerometer and gyroscope) to study
human activities (sitting, walking, stairs).

## Structure
- `data/raw/` – original IMU recordings  
- `data/clean/` – cleaned and preprocessed signals  
- Python scripts (cleaning, feature extraction, visualization)  
- `figures/` – generated plots  
- final PDF report

## Pipeline
1. Raw data exploration  
2. Cleaning and preprocessing (resampling at 30 Hz, interpolation, outlier handling, smoothing)  
3. Feature engineering (magnitude, rolling statistics, FFT)  
4. Visualization and analysis

## Requirements
Python 3, numpy, pandas, scipy, matplotlib

## How to run
```bash
python data_cleaning.py
python feature_engineering.py
python visualization.py
