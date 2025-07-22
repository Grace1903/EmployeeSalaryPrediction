# EmployeeSalaryPrediction

A web application to predict whether an individual's annual income exceeds $50,000 using the "Adult" census dataset and a machine learning model.

## 🚀 Features

- **Accurate Predictions:** Utilizes a trained classification model based on real census data.
- **Interactive Web Interface:** User-friendly form built with Streamlit for data input.
- **Instant Results:** Predicts if income is ≤$50K or >$50K in real-time.
- **Easy Setup:** Simple instructions for running the app locally.

## 📊 Dataset

The model is trained on the [Adult Census Income dataset](https://archive.ics.uci.edu/ml/datasets/adult) from the UCI Machine Learning Repository.  
Key attributes include:
- Age
- Workclass
- Education
- Marital-status
- Occupation
- Relationship
- Race
- Sex
- Capital-gain
- Capital-loss
- Hours-per-week
- Native-country

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** scikit-learn
- **Web App Framework:** Streamlit

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Grace1903/EmployeeSalaryPrediction.git
   cd EmployeeSalaryPrediction
   ```

2. **Install dependencies:**
   ```bash
   pip install streamlit pandas numpy scikit-learn
   ```

## ▶️ Usage

Start the Streamlit app with:
```bash
streamlit run app.py
```
This will open the application in your browser, where you can input data and receive predictions.

## 📂 Project Structure

```
EmployeeSalaryPrediction/
├── data/
│   └── adult.csv         # Training dataset
├── model.pkl             # Trained model file
├── app.py                # Streamlit application
└── README.md             # Project documentation
```

## 🤝 Contributing

Contributions are welcome!  
Feel free to open issues or submit pull requests to improve this project.

## 📄 License

This project is licensed under the MIT License.



