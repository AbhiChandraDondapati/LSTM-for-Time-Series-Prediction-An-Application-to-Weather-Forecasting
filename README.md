# 🌦 LSTM-for-Time-Series-Prediction-An-Application-to-Weather-Forecasting

This project focuses on predicting weather conditions using the Long Short-Term Memory (LSTM) neural network model. By leveraging 20 years of historical weather data from Delhi, the project aims to forecast temperature and other weather conditions accurately. 

---

## 📌 Abstract

Forecasting weather conditions is a challenging task due to the complex and dynamic nature of meteorological data. This project introduces a weather prediction model using LSTM, a type of recurrent neural network, to predict temperature based on 20 years of historical data. By addressing issues such as data inconsistency and null values, the model achieves a prediction accuracy of 73.15%.

---

## ❓ Problem Definition

Weather predictions are crucial for planning and ensuring safety against natural disasters such as floods and heatwaves. Traditional numerical models require significant computational power and time. This project proposes using deep learning techniques, specifically LSTM, to forecast weather conditions more efficiently and accurately.

---

## 🎯 Project Objectives

- To collect a comprehensive dataset of weather conditions over 20 years.
- To preprocess and clean the data for effective training.
- To build an LSTM model for predicting temperature and other weather parameters.
- To validate the model's accuracy by comparing predicted results with real-time data.

---

## ⚠️ Challenges

- **Data Collection:** Acquiring a dataset with sufficient entries and relevant information was a primary challenge.
- **Data Inconsistency:** Managing null values and ensuring uniform data formats.
- **Model Training:** Fine-tuning the LSTM model to optimize accuracy.

---

## 📦 Deliverables

- A cleaned and preprocessed dataset ready for analysis.
- An LSTM-based weather prediction model.
- Visualization of predicted vs. actual temperature data.
- A detailed analysis report and documentation.

---

## 📚 Literature Review

- Explored various approaches to time-series forecasting, including ARIMA and LSTM.
- LSTM was chosen due to its ability to manage long-term dependencies and provide higher accuracy for sequential data.
- Studies indicated that LSTM performs better than traditional models in handling time-series weather data.

---

## 🗄 Description of the Dataset

- **Source:** Historical weather data for Delhi spanning 20 years.
- **Shape:** 100,990 entries and 20 columns.
- **Key Features:** 
  - `datetime_utc`, `temperature`, `humidity`, `rain`, `snow`, `wind speed`, etc.
- **Preprocessing Steps:**
  - Handled null values by imputation or removal.
  - Converted date-time formats to standard ISO format.
  - Scaled features for uniform training.

---

## ⚙️ Proposed Methodology

- **1. Data Collection:**
  - Gathered data from reliable meteorological sources.
- **2. Data Preprocessing:**
  - Cleaned null values and standardized data formats.
  - Performed feature scaling and normalization.
- **3. Model Building:**
  - Used a two-layer LSTM with 100 and 64 hidden units.
  - Implemented fully connected layers with sizes 32 and 1.
- **4. Training:**
  - Trained the model with 18 years of data for 200 epochs.
- **5. Prediction:**
  - Forecasted temperature for the next 2 years with an accuracy of 73.15%.

---

## 📊 Experimental Results

- **Training Accuracy:** 73.15%
- **Training Loss:** 26.84%
- **Key Findings:**
  - LSTM effectively captured seasonal patterns and long-term dependencies.
  - Model performed well for moderate weather conditions but showed minor inaccuracies at extreme temperatures.
- **Visualization:**
  - Displayed graphs for predicted vs. actual temperatures.
  - Used loss plots to show model performance per epoch.

---

## 🏁 Conclusion and Future Scope

- **Conclusion:**
  - The LSTM model demonstrated effective performance in predicting weather conditions with reasonable accuracy.
  - Managed to forecast temperature trends accurately for most parts of the year.

- **Future Scope:**
  - Exploring transductive LSTM with a quadratic cost function for improved accuracy.
  - Expanding the model to predict other weather parameters like rainfall and wind speed.
  - Integrating real-time data feeds for continuous model retraining.

## All the outputs and results can be shown clearly in code.ipynb file.

---

## 📚 References

1. Kumar, N., & Jha, G. K. (2013). A time-series ANN approach for weather forecasting.
2. Salman, A. G., et al. (2018). LSTM for weather forecasting.
3. Greff, K., et al. (2016). LSTM: A search space odyssey.
4. Zhao, Z., et al. (2017). LSTM for short-term traffic forecast.
5. Karevan Z, Suykens JAK. (2020). Transductive LSTM for time-series prediction.


---

**Developed by:** [AbhiChandraDondapati](https://github.com/AbhiChandraDondapati)  


