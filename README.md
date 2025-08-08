# Wine-Quality-Prediction
A machine learning project to predict wine quality using chemical properties. This project applies multiple classification algorithms — Random Forest, Stochastic Gradient Descent, and Support Vector Classifier — and compares their performance.

---

## 📁 Project Structure

├── WineQT.csv # Dataset (red wine quality data)
├── 5.Wine Quality Prediction.ipynb # Jupyter Notebook with full implementation
├── README.md # Project documentation
├── requirements.txt # Python dependencies

yaml
Copy
Edit

---

## 🧠 Algorithms Used

- Random Forest Classifier 🌲
- Stochastic Gradient Descent (SGD) Classifier ⚙️
- Support Vector Classifier (SVC) ➗

---

## 📊 Dataset Overview

- Source: Red wine quality dataset
- Features: 11 physicochemical properties (e.g., acidity, sulphates, alcohol)
- Target: Wine quality (score between 3 and 9)

---

## 🔬 Key Features

- **Data Preprocessing:** Missing value handling, scaling, and train-test splitting
- **Exploratory Data Analysis:** Heatmaps, correlation analysis
- **Feature Scaling:** StandardScaler
- **Model Training & Evaluation:** Accuracy, Confusion Matrix, Classification Reports
- **Class Imbalance Handling:** Option to apply `class_weight='balanced'`

---

## 🔧 Libraries Used

- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` & `seaborn` – for visualization
- `scikit-learn` – for machine learning models and evaluation

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/wine-quality-prediction.git
    cd wine-quality-prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook and open the project:
    ```bash
    jupyter notebook
    ```

---

## 📝 Results

| Model           | Accuracy |
|----------------|----------|
| Random Forest  | ~**X%**  |
| SGD Classifier | ~**Y%**  |
| SVC            | ~**Z%**  |

> Replace X, Y, Z with the actual values from your notebook.

---

## 📈 Visualizations

- **Correlation Heatmap** between chemical properties
- **Confusion Matrix** of predictions
- **Quality Distribution Plot** (optional)

---

## 🤖 Future Improvements

- Use `GridSearchCV` for hyperparameter tuning  
- Try advanced models like XGBoost or LightGBM  
- Apply SMOTE for class balancing  
- Deploy the model with Flask or Streamlit

---

## 📚 References

- UCI Wine Quality Dataset  
- scikit-learn Documentation

---

## 🙌 Acknowledgments

Thanks to the UCI Machine Learning Repository and the open-source community.

---

## 📬 Contact

For questions or collaboration, reach out via GitHub:  
[https://github.com/ManchikantiGayathri](https://github.com/ManchikantiGayathri)

---

## 🪪 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
