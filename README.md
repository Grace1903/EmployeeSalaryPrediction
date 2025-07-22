# EmployeeSalaryPrediction
Income Prediction Web App
This project uses the "Adult" census dataset to predict whether an individual's income is greater than $50,000 per year. 
A machine learning model was trained on this data and has been deployed as a simple, interactive web application using Streamlit.

🚀 FeaturesData-driven Predictions: Uses a classification model trained on real census data.
Interactive Web Interface: A user-friendly form built with Streamlit to input an individual's details.
Real-time Classification: Instantly predicts whether the income bracket is <=50K or >50K.
Easy to Use: No complex setup required to run the application locally.

📊 DatasetThis model is trained on the Adult Census Income dataset, sourced from the UCI Machine Learning Repository. The dataset contains 14 attributes for each individual, such as:AgeWorkclassEducationMarital StatusOccupationRelationshipRaceSexHours per weekNative Country

🛠️ Tech Stack & LibrariesLanguage: Python 3.8+Data Processing: Pandas, NumPyMachine Learning: Scikit-learnWeb Application: Streamlit⚙️ 
Installation & SetupTo set up and run this project on your local machine, please follow these steps.Clone the repository (or download the files):git clone https://github.com/Grace1903/EmployeeSalaryPrediction.git

you can install the necessary libraries directly using pip.pip install streamlit pandas numpy scikit-learn
▶️ How to Run the AppWith the libraries installed, you can start the web application by running the following command from your project's root directory:streamlit run app.py
This will launch the application in your web browser, where you can input data to get an income prediction.

📂 Project StructureA typical structure for this project would be:
income-prediction-app/
├── data/
│   └── adult.csv           # The dataset for training
├── model.pkl               # The saved (pickled) classification model
├── app.py                  # The main Streamlit application script
└── README.md               # This file

📄 LicenseThis project is licensed under the MIT License.