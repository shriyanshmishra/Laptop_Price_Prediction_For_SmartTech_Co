# Laptop Price Prediction for SmartTech Co.  

## 🌟 Project Overview  
This project aims to develop a machine learning model to predict laptop prices accurately based on key specifications such as brand, RAM, CPU, GPU, and screen resolution. The insights generated from this model will empower **SmartTech Co.** in strategic decision-making, market positioning, and pricing strategies.  

## 🛠️ Problem Statement  
Laptops vary significantly in price based on their features and brand. **SmartTech Co.** requires a reliable prediction model to help them understand the factors influencing laptop prices and predict prices for new or lesser-known brands.  

## 📊 Dataset  
The dataset used for this project includes the following columns:  
- `Company`: The brand of the laptop.  
- `TypeName`: Type of laptop (e.g., Notebook, Ultrabook, 2-in-1 Convertible).  
- `Inches`: Screen size.  
- `ScreenResolution`: Resolution of the laptop screen.  
- `Cpu`: Processor specifications.  
- `Ram`: RAM size in GB.  
- `Memory`: Storage details.  
- `Gpu`: Graphics card details.  
- `OpSys`: Operating System.  
- `Weight_Kg`: Weight of the laptop in kilograms.  
- `Price`: Price of the laptop (Target Variable).  

## ⚙️ Workflow  
### 1. **Data Exploration and Preprocessing**  
- Visualized trends in laptop prices.  
- Handled missing values and outliers.  
- Encoded categorical variables for machine learning compatibility.  
- Performed feature engineering for better model performance.  

### 2. **Model Development**  
- Trained and compared three machine learning models:  
  - **Linear Regression**  
  - **Random Forest Regressor**  
  - **Decision Tree Regressor**  
- Evaluated models using R² Score and Mean Absolute Error (MAE).  
- Achieved the highest accuracy with **Random Forest (R²: 0.83, MAE: 0.19)**.  

### 3. **Insights and Interpretability**  
- Key factors influencing laptop prices:  
  - RAM, GPU, and screen resolution significantly impact pricing.  
- Lesser-known brands: The model predicts prices with reasonable accuracy.  
- High-end vs. budget laptops: The model performs well across different price ranges.  

## 🚀 Key Features  
- **Data Preprocessing**: Outlier handling, missing value imputation, and encoding categorical variables.  
- **Feature Engineering**: Enhanced model performance through derived features.  
- **Model Evaluation**: Detailed comparison of multiple regression models.  
- **Interpretability**: Feature importance analysis to identify key pricing factors.  


## 📊 Results  
| Model               | R² Score | MAE    |  
|---------------------|----------|--------|  
| **Random Forest**   | 0.83     | 0.19   |  
| **Linear Regression** | 0.74     | 0.24   |  
| **Decision Tree**   | 0.73     | 0.23   |  

## 💻 Tech Stack  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

## 🔮 Future Improvements  
- Incorporate additional features, such as laptop release year.  
- Enhance model performance with hyperparameter tuning.  
- Deploy the model using Flask or FastAPI for real-time predictions.  

## 📂 How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/Laptop-Price-Prediction.git  


