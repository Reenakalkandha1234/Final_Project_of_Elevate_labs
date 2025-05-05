# Final_Project_of_Elevate_labs

# 🏠 Airbnb Dynamic Pricing Recommendation Engine

This project is a data-driven solution to help Airbnb hosts determine optimal nightly prices for their listings. By analyzing historical booking data, we developed a dynamic pricing engine that suggests rates based on factors like location, seasonality, and listing quality.

## 📌 Objective
To analyze historical Airbnb data and build a recommendation engine that suggests optimal prices for listings, aiming to maximize revenue and maintain competitive pricing.

## 🛠️ Tools & Technologies
- **Python**: Data preprocessing, feature engineering, regression modeling
- **Pandas, NumPy, Scikit-learn, SHAP**: Core data science libraries
- **Matplotlib, Seaborn**: Visualization for exploratory data analysis
- **Tableau**: Interactive dashboard for price exploration
- **Excel**: Preliminary data cleaning and inspection .

## 🧠 Key Features
- Dynamic pricing recommendation function
- Analysis of pricing influencers: city, property type, reviews, and stay duration
- Interactive Tableau dashboard with filters and price sliders
- Model interpretability using SHAP values
- Regression models for price prediction

## 🔄 Workflow
1. **Data Cleaning**: Removed nulls and irrelevant data
2. **Feature Engineering**: Created variables like `TotalStay`, `IsHighSeason`, `ReviewLevel`, etc.
3. **EDA**: Explored data trends across locations and seasons
4. **Modeling**: Used Random Forest and Linear Regression to predict prices
5. **Model Tuning & Evaluation**: Applied GridSearchCV for optimization
6. **Dashboard**: Built an interactive Tableau dashboard
7. **Deployment Logic**: Implemented a `recommend_price()` function

## 📊 Deliverables
- `Airbnb_project.ipynb`: Jupyter notebook with full analysis and model development
- `Airbnb Hospitality Analysis Dashboard.twbx`: Tableau dashboard for price exploration
- `Airbnb_Dynamic_Pricing_Recommendation_Report.pdf`: Final 2-page project report
- `README.md`: Project overview and instructions

## 📈 Dashboard Preview
Check out the Tableau dashboard to interactively explore suggested pricing across different filters such as city, property type, and review scores.

## 📄 Report
The final report summarizes the objective, methodology, tools used, steps taken, and project conclusion in a concise 2-page PDF format.

## 🤖 Future Improvements
- Real-time data integration from Airbnb APIs
- Include competitor pricing and demand forecasting
- Deploy as a web application for broader usability

---


