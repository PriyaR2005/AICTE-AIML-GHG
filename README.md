# AICTE-AIML-GHG

#📊 Supply Chain Emission Factor Prediction (AICTE GHG Week 2)
This repository presents an end-to-end data science project focused on predicting Supply Chain Emission Factors with Margins for U.S. industries and commodities using historical data from 2010–2016. This task was undertaken as part of AICTE GHG (Green House Gas) Week 2 challenge.

#📁 Dataset
The dataset used is an Excel file containing detailed emission factors for various industries and commodities, categorized by year. Key features include:

Substance (e.g., carbon dioxide, methane)

Unit of Measurement

Emission Factors

Source Type (Commodity or Industry)

#🚀 Project Workflow
1.Data Preprocessing

Combined data from multiple sheets (across years)

Cleaned and standardized column names

Encoded categorical variables (e.g., Substance, Unit, Source)

Removed unnecessary columns and handled nulls

2.Exploratory Data Analysis (EDA)

Distribution plots

Correlation matrix

Top 10 emitting industries visualization

3.Feature Engineering

One-hot encoding for Source

Scaling numeric features using StandardScaler

4.Modeling

Split into train-test sets

Models used:

Random Forest Regressor (default)

Linear Regression

Random Forest with Hyperparameter Tuning (GridSearchCV)

Evaluated using:

RMSE

R² Score

5.Model Saving

Best model and scaler are saved using joblib for later deployment.

#📈 Results
Model	RMSE	R² Score
Random Forest (Default)	~	~
Linear Regression	~	~
Random Forest (Tuned)	✅ Best	✅ Best

(Replace ~ with actual values from the script outputs)

#🧪 Technologies Used
Python 🐍

Pandas, NumPy, Seaborn, Matplotlib

Scikit-learn

Joblib

Jupyter/Colab

#📦 Folder Structure
bash
Copy
Edit
.
├── aicteghgweek2.py           # Main script
├── models/
│   ├── LR_model.pkl           # Saved tuned model
│   └── scaler.pkl             # Saved StandardScaler
└── README.md
#📌 How to Run
bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/aicteghgweek2.git
cd aicteghgweek2

# Install dependencies
pip install -r requirements.txt

# Run the script (make sure the Excel dataset is available)
python aicteghgweek2.py
⚠️ Note: Ensure you have the dataset Excel file and update the excel_file path in the script.

#📬 Contact
For queries or collaboration, feel free to connect at [your-email@example.com] or raise an issue in the repo.
