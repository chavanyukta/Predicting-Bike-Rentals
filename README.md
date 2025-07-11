# Predicting Bike Rentals

## Project Overview
This project predicts bike rental demand in Seoul using machine learning techniques. By analyzing weather, temporal, and holiday features, the models estimate hourly bike rental counts to help improve resource planning and service efficiency.

## Dataset
The dataset contains hourly records of bike rentals in Seoul from 2017 to 2018, including features such as temperature, humidity, wind speed, visibility, solar radiation, rainfall, snowfall, seasons, holidays, and functioning days.

## Analysis
The project involves data cleaning, exploratory data analysis (EDA), feature engineering (including encoding categorical variables), and regression modeling. Three models—Linear Regression, Kernel Ridge Regression, and Support Vector Regression (SVR)—are trained and evaluated using Root Mean Squared Error (RMSE) and cross-validation techniques. Hyperparameter tuning is performed to optimize model performance.

## Dataset Source
The dataset is publicly available and described in the paper:  
*Sathishkumar V E, Jangwoo Park, and Yongyun Cho. "Using data mining techniques for bike sharing demand prediction in metropolitan city." Computer Communications, Vol.153, pp.353-366, March 2020.*

## Project Structure
- `code file.ipynb` — Jupyter notebook containing the full analysis and modeling workflow  
- `SeoulBikeData.csv` — Dataset file (to be downloaded separately)  
- `Predicting Bike Rentals Report.pdf` — Detailed project report (uploaded)

## How to Run the Code
1. Ensure Python 3.6+ is installed.  
2. Install required libraries:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib
3. Place the dataset (SeoulBikeData.csv) in the same directory as the notebook.
4. Open and run the notebook (code file.ipynb) to reproduce the analysis and results.

## Project Report
A detailed project report titled [Predicting Bike Rentals Report.pdf](./Predicting%20Bike%20Rentals%20Report.pdf) has been uploaded.  
Click the link to view comprehensive explanations of the methodology, experiments, and findings.

## Contact
Name: Yukta Sanjiv Chavan
Email: chavanyukta@gmail.com


