#  Enhanced Solar Power Output Forecasting using Ensemble Learning

This project presents a machine learning-based approach to accurately forecast solar power output by integrating real-time weather sensor data with historical solar generation records. The model leverages advanced ensemble learning techniques to provide high-accuracy predictions, supporting smart grid planning and renewable energy optimization.

---

## 📌 Project Highlights

- Developed an ensemble stacking model combining **XGBoost**, **LightGBM**, **CatBoost**, and **SVR**, achieving a high **R² score of 95.17%**.
- Integrated and preprocessed **real-time weather** and **solar generation** datasets through timestamp alignment and feature engineering.
- Applied **EDA**, **correlation analysis**, and **model optimization** using **GridSearchCV** for robust performance.
- Evaluated models using key metrics: **MAE**, **RMSE**, and **R² Score**.

---

## 📊 Dataset

Two real-world datasets were used:

1. **Solar Generation Data**: Timestamped power output readings from a solar PV plant.
2. **Weather Sensor Data**: Solar irradiance, ambient/module temperature, humidity, wind direction, and weather status.

> 🔗 Data synchronized using timestamps and preprocessed to form a unified training dataset.

---

##  Tech Stack

- **Languages**: Python 3.10
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `XGBoost`, `LightGBM`, `CatBoost`
- **Tools**: Jupyter Notebook, GridSearchCV

---

## ⚙️ Model Workflow

1. **Data Collection & Fusion**  
2. **Preprocessing & Feature Engineering**  
3. **Exploratory Data Analysis (EDA)**  
4. **Model Training (Linear, DT, RF, Stacking)**  
5. **Ensemble Stacking Optimization**  
6. **Model Evaluation**

---

## 📈 Results

| Model                | R² Score | MAE    | RMSE   |
|---------------------|----------|--------|--------|
| Linear Regression   | 88.65%   | 0.3907 | 0.4972 |
| Decision Tree       | 90.27%   | 0.3485 | 0.4511 |
| Random Forest       | 94.51%   | 0.2615 | 0.3598 |
| **Ensemble Stacking** | **95.17%** | **0.2301** | **0.3378** |

---

##  Key Learnings

- Importance of **data fusion** for improving model performance in energy forecasting.
- Ensemble models enhance generalizability by combining strengths of individual algorithms.
- Preprocessing and **feature relevance** are critical in achieving high predictive accuracy.

---

##  Future Work

- Incorporate time-series models like **LSTM** or **GRU** for multi-day forecasting.
- Use real-time **satellite/cloud cover data** for weather condition precision.
- Deploy the model for **real-time energy forecasting** in smart grids or edge devices.

---

##  Author

**Riya Kesharwani**  
📫 [riya10.work@gmail.com](mailto:riya10.work@gmail.com)  
🔗 [LinkedIn](http://www.linkedin.com/in/riyakesharwani) | [Portfolio](https://riya102002.github.io/Portfolio/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
