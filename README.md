# SpaceX Falcon 9 Landing Prediction

## 🚀 Project Overview
This project predicts the success of SpaceX Falcon 9 first-stage landings. With launch costs reaching **$62 million** per mission, the ability to reuse the first stage is a critical factor in the commercial space industry. This predictive model achieves an **83.33% accuracy** in determining whether a booster will land successfully.

## ✨ Key Features
* **Data Integration:** Combined raw data from the SpaceX API and Wikipedia web scraping.
* **Interactive Analytics:** Built a **Plotly Dash** dashboard for real-time mission filtering and success visualization.
* **Geospatial Insights:** Developed **Folium** maps to visualize launch site proximity to coastlines and recovery zones.
* **Machine Learning:** Optimized and compared Logistic Regression, SVM, KNN, and Decision Tree models using `GridSearchCV`.



## 🛠️ The Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Tools:** SQL (IBM DB2), Jupyter Notebooks, Folium, Plotly Dash

## 📊 Results & Conclusions
* **Best Model:** All models achieved an identical **83.33% accuracy** on the test set. The Decision Tree model is highlighted for its high interpretability.
* **Primary Findings:** * Success rates are highly correlated with **Flight Number** (experience).
    * Landing success is dependent on the target orbit; **ES-L1, SSO, HEO, and VLEO** show the highest success rates.
    * Launch site **KSC LC-39A** has the highest count of successful landings.
