# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

This project performs exploratory data analysis, interactive visual analytics, and predictive modeling to predict whether the first stage of SpaceX Falcon 9 rockets will land successfully.


## 📝 Project Overview

SpaceX aims to perform controlled landings of the Falcon 9 first stage to enable rocket reuse and reduce launch costs. This project leverages SpaceX launch data to analyze historical trends and build machine learning models to predict successful landings.

## 📂 Project Folder Structure
 - ├── Data Collection/ # Scripts and notebooks for gathering data
 - ├── Web Scraping/ # Code to scrape relevant SpaceX launch data
 - ├── Data Wrangling/ # Data cleaning and preprocessing notebooks/scripts
 - ├── EDA with SQL/ # Exploratory data analysis using SQL queries
 - ├── EDA with Visualization/ # Visualization notebooks (matplotlib, seaborn, etc.)
 - ├── Interactive Visual Analytics with Folium/ # Interactive mapping and geospatial analysis
 - ├── Interactive Dashboard with Plotly Dash/ # Dash app for interactive data exploration
 - ├── Complete the Machine Learning Prediction/ # Model training, tuning, and evaluation

---

## 🚀 Key Components

- **🔍 Exploratory Data Analysis (EDA):**  
  Analyze launch site features, payload mass, and landing outcomes with SQL and visualizations.

- **🗺️ Interactive Visual Analytics:**  
  Use Folium to map launch sites and their proximities to infrastructure and geography.

- **📊 Interactive Dashboard:**  
  Build with Plotly Dash — includes dropdown menus, sliders, pie charts, and scatter plots for dynamic exploration of launch data.

- **🤖 Predictive Modeling:**  
  Train and tune classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict landing success, optimizing hyperparameters with Grid Search.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- SQL (for data querying)
- Plotly Dash (interactive dashboards)
- Folium (interactive maps)
- Matplotlib & Seaborn (visualizations)
- Jupyter Notebooks (development environment)

---

## ⚙️ Installation

1. Clone the repository:


git clone https://github.com/yourusername/spacex-landing-prediction.git
cd spacex-landing-prediction
pip install -r requirements.txt

## 🎯 Usage
1. Data Collection & Wrangling
Explore and run scripts/notebooks in Data Collection/, Web Scraping/, and Data Wrangling/ folders to gather and prepare data.

2. Exploratory Data Analysis
Run notebooks in EDA with SQL/ and EDA with Visualization/ for insights using SQL queries and visualizations.

3. Interactive Visual Analytics
Launch Folium maps from the Interactive Visual Analytics with Folium/ folder to explore launch site proximities.

4. Interactive Dashboard
Run the Plotly Dash app to explore launch success interactively: python Interactive\ Dashboard\ with\ Plotly\ Dash/spacex_dash_app.py

5. Machine Learning Prediction
Run the model training notebook/script in Complete the Machine Learning Prediction/ for predictive analysis.

## 📊 Key Insights
 - Launch site CCAFS SLC-40 has the largest number of successful launches.

 - Launch sites differ in success rates and payload capacities.

 - Payload mass influences landing success.

 - Decision Tree classifier with tuned hyperparameters achieves ~87.5% accuracy.

 - Logistic Regression shows strong performance (~83.3% accuracy).

 - The interactive dashboard helps uncover detailed insights across sites and payload ranges.

## 🔮 Future Work
Integrate environmental factors (weather, wind speed) into models.
Deploy dashboard to cloud services for public access.
Explore ensemble and deep learning methods for improved prediction accuracy.

[Download README.md](sandbox:/mnt/data/README.md)
