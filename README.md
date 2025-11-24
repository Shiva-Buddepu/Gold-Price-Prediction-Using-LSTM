# Gold Price Prediction Using LSTM

This project focuses on forecasting **Gold Prices** using a **Long Short-Term Memory (LSTM)** deep learning model.  
The dataset contains **daily gold price records from 2013 to 2023**, including features such as Date, Price, Open, High, Low, Volume, and Change %.  
The goal is to analyze historical data, prepare it for time-series modeling, and build an LSTM network that can accurately predict future gold prices.

---

## Dataset
**Dataset Name:** Gold Price (2013–2023)  
**Columns Included:**
- Date  
- Price  
- Open  
- High  
- Low  
- Vol.  
- Change %

---

##  Project Workflow

### 1. Importing Libraries
Imported all required libraries for data handling, visualization, preprocessing, and model building.

### 2. Reading Dataset
Loaded the gold price dataset into a pandas DataFrame.

### 3. Dataset Overview
Performed initial inspection:
- First & last rows  
- Structure  
- Missing values  
- Summary statistics  

### 4. Dataset Basic Information
Checked:
- Data types  
- Column formats  
- Memory usage  

### 5. Data Preparation
- Converted Date column to datetime format  
- Sorted dataset by date  
- Filtered required features  

### 6. Visualizing Gold Price History Data
Plotted:
- Gold Price trend  
- Open, High, Low price variations  

### 7. Splitting Data into Training & Test Sets
Data split into:
- **Training Set:** For model learning  
- **Test Set:** For model evaluation  

### 8. Data Scaling
Used **MinMaxScaler** to normalize values between 0 and 1.

### 9. Restructuring Data & Creating Sliding Window
Created sequences for LSTM input using a fixed window size (e.g., 60 days).

### 10. Converting Data to Numpy Arrays
Converted training and test sets into numpy arrays for LSTM compatibility.

### 11. Creating an LSTM Network
Built an LSTM-based deep learning model:
- LSTM layers  
- Dense layers  
- Dropout  
- Adam optimizer  

### 12. Model Evaluation
Evaluated model performance using:
- RMSE  
- MAE  
- Visualization of predicted vs. actual values  

### 13. Visualizing Results
Generated:
- Prediction vs. Actual Price Plot  
- Future trend observation  

---
