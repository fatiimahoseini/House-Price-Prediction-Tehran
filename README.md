# Tehran Apartment Price Prediction 🏠

Predicting apartment prices in Tehran using real-world data and machine learning. 🚀

---

## Project Overview

Estimate apartment prices based on features like:

- 📏 Area (square meters)  
- 🛏 Number of rooms  
- 🚗 Parking availability  
- 📦 Warehouse availability  
- 🛗 Elevator availability  
- 📍 Approximate address  

Dataset: ~4000 real entries from Tehran.

---

## 🧹 Data Preparation

-  Removed price outliers with IQR method for cleaner data.  
-  Scaled numerical features (`Area`, `Room`) using StandardScaler.  
-  Encoded `Address` with OneHotEncoder.  
-  Split data: 80% training, 20% testing.

---

##  Modeling

-  Baseline model: Linear Regression.  
-  Evaluated using MAE, MSE, RMSE, and R² metrics.  
-  Visualized actual vs predicted prices with scatter plot and fitted regression line.

---

## 🚀 Next Steps

-  Test regularized regression models (Ridge, Lasso).  
-  Explore advanced models (Random Forest, XGBoost).  
-  Build a simple user interface for price prediction.

---

## Usage

1. Clone the repository  
2. Install dependencies from `requirements.txt`  
3. Run the Jupyter notebook for data processing, modeling, and evaluation  

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

Questions or collaboration? Feel free to reach out!
[Fatima Hosseini] - [fatiimahoseini@gmail.com] - [Linkedin](https://www.linkedin.com/in/fatiimahoseini)

---

*This project is a work in progress and will be updated regularly.* 🔄
