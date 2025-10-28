# 🌍 Global Temperature Forecasting using Time Series Modeling
<p align='center'>
    <img src="./read/difference from date average.png" alt="Texte alternatif" width="700"/>
</p>

## 📘 Project Overview

This mini-project aims to **analyze and predict global temperature anomalies** using time series forecasting techniques.
In the context of **climate change**, accurate temperature forecasting is crucial for understanding long-term warming trends and assessing their environmental impacts.

The notebook `main.ipynb` provides a full workflow — from data preprocessing to model evaluation — using the dataset `temperature.csv`.

---

## 🧩 Dataset

The dataset (`temperature.csv`) contains historical **global temperature anomaly data**, measured relative to a baseline average.
Each record includes:

* **Date / Year**
* **Temperature anomaly (°C)**

The data has been cleaned and formatted to build a continuous time series suitable for forecasting.

---

## 🧠 Methodology

The project follows a structured **data science pipeline**:

1. **Data Loading & Cleaning**

   * Import and format the CSV data
   * Handle missing or inconsistent values
   * Convert temporal data into a time-indexed series

2. **Exploratory Data Analysis (EDA)**

   * Visualize the temperature evolution over time
   * Detect long-term trends and seasonal patterns

   * line plot of temperature anomalies over time / histogram or density plot showing anomaly distribution
   <p align='center'>
      <img src="./read/temperature anomaly over the years.png" alt="Texte alternatif" width="350"/>
      <img src="./read/distribution of global temperature anomalies.png" alt="Texte alternatif" width="350"/>
   </p>

3. **Modeling & Forecasting**

   * Apply statistical model ( ARIMA )
   * Tune hyperparameters for best forecasting accuracy

---

## ⚙️ Requirements

You can install the required Python libraries with:

```bash
pip install -r requirements.txt
```

Or manually install the key dependencies:

```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

---

## ▶️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/BravoDiego/temperature-forecasts.git
   cd global-temperature-forecast
   ```

2. Open the notebook:

   ```bash
   jupyter notebook main.ipynb
   ```

3. Execute the cells sequentially to reproduce all results and plots.

---

## 📈 Results

The forecasting model successfully reproduces the **global warming trend** and provides a **short-term prediction** of temperature anomalies.

<p align='center'>
   <img src="./read/forecast temperature.png" alt="Texte alternatif" width="700"/>
</p>

---

## 🚀 Future Improvements

* Incorporate regional temperature data for finer granularity
* Compare multiple forecasting models (LSTM vs Prophet vs SARIMA)
* Add uncertainty quantification and ensemble methods
* Deploy the model via a lightweight Flask or Streamlit app for real-time predictions

---

## 🧑‍💻 Author

**[Your Name]**
Data Science & Climate Modeling Enthusiast
📫 Contact: [[diego.bravo.contact@gmail.com](mailto:diego.bravo.contact@gmail.com)]

---

> “Climate modeling is not only about prediction — it’s about understanding our planet’s story through data.”

## 🙏 Acknowledgements
- Thanks to [Machine Learnia](https://www.youtube.com/c/clearcode) for the idea
- Datas by [NCEI](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series) 
