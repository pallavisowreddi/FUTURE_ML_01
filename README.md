# 📊 Sales & Demand Forecasting
### Future Interns | Machine Learning Track | Task 01 | FUTURE_ML_01

## 📌 About This Project
Built a machine learning model to forecast future sales 
using real retail business data. The goal is to help 
businesses plan inventory, manage cash flow, and prepare 
staffing using data-driven predictions.

## 🛠️ Tools & Technologies
- Python
- Google Colab
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## 📁 Dataset
- **Name:** Superstore Sales Dataset
- **Source:** Kaggle
- **Records:** 9,994 rows × 21 columns
- **Period:** 2019 – 2022

## ✅ Key Features Implemented

**1. Data Cleaning**
- Loaded real retail sales data
- Fixed date formats & handled missing values
- Grouped transactions into daily sales totals

**2. Feature Engineering**
- Day, month, quarter, year extraction
- Weekend & holiday season flags
- Lag features (1-day, 7-day, 30-day)
- Rolling averages (7-day, 30-day)

**3. Models Trained**
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor ✅ Best Model

**4. Model Evaluation**
| Metric | Value |
|--------|-------|
| Best Model | Gradient Boosting |
| Avg Daily Error (MAE) | $2,174 |

**5. Visualizations**
- Monthly Sales Trend
- Sales by Category
- Seasonality Heatmap
- Model Comparison Chart
- Forecast vs Actual
- 30-Day Future Forecast

## 🔮 30-Day Forecast Results
- 💰 Total Expected Revenue: $57,099
- 📅 Average Daily Sales: $1,903
- 📈 Peak Sales Month: November & December

## 💡 Business Insights
- Holiday season (Nov–Dec) drives highest sales
- Weekends consistently outperform weekdays
- Businesses can use this forecast to:
  - Plan inventory before peak seasons
  - Schedule staff during high-demand periods
  - Manage cash flow using monthly forecasts
  - Run promotions during predicted slow periods

## 📸 Output Screenshots
All output screenshots are included in this repository.

## 🔗 Links
- 📓 Google Colab Notebook: https://colab.research.google.com/drive/1Upp4jvt44WqC5nZfLrVXxIzP4gU53v_F#scrollTo=3PVVO3muMxxB

## 👤 Author
- **Internship:** Future Interns
- **Track:** Machine Learning
- **Task:** 01 — Sales & Demand Forecasting
