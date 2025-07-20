IBM Skillbuild - Employee Salary Prediction
A machine learning project that predicts whether an employee earns more than $50K annually based on demographic and work-related features.

Project Overview
This project uses the Adult Census Income dataset to build a classification model that predicts salary ranges. The application includes:

Data Analysis & Preprocessing: Jupyter notebook with exploratory data analysis
Machine Learning Models: Comparison of multiple algorithms (Logistic Regression, Random Forest, Gradient Boosting)
Web Application: Interactive Streamlit app for real-time predictions
Features
📊 Interactive Web Interface: User-friendly Streamlit application
🤖 Multiple ML Models: Trained and compared various algorithms
📈 Data Visualization: Comprehensive exploratory data analysis
🔄 Batch Predictions: Upload CSV files for bulk predictions
📱 Responsive Design: Works on desktop and mobile devices
Files Structure
IBM-skillbuild/
├── app.py                           # Streamlit web application
├── employee_salary_prediction.ipynb # Jupyter notebook with analysis
├── best_model.pkl                   # Trained machine learning model
├── adult 3.csv                      # Dataset
└── README.md                        # Project documentation
Installation & Setup
Clone the repository:

git clone https://github.com/YOUR_USERNAME/IBM-skillbuild.git
cd IBM-skillbuild
Install required packages:

pip install streamlit pandas scikit-learn joblib matplotlib seaborn
Run the application:

streamlit run app.py
Usage
Web Application
Open the Streamlit app in your browser
Adjust the input parameters in the sidebar:
Age, Work Class, Education Level
Marital Status, Occupation, Relationship
Race, Gender, Capital Gains/Losses
Hours per week, Native Country
Click "Predict Salary Class" to get the prediction
Batch Predictions
Prepare a CSV file with the required columns
Upload the file using the file uploader
Download the results with predictions
Model Performance
The best performing model achieved:

Accuracy: 85.7%
Algorithm: Gradient Boosting Classifier
Features: 13 demographic and work-related attributes
Dataset
The project uses the Adult Census Income dataset with the following features:

Age, Work Class, Final Weight, Education Number
Marital Status, Occupation, Relationship, Race
Gender, Capital Gain, Capital Loss, Hours per Week
Native Country
Target Variable: Income (<=50K or >50K)

Technologies Used
Python: Core programming language
Streamlit: Web application framework
Scikit-learn: Machine learning library
Pandas: Data manipulation and analysis
Matplotlib/Seaborn: Data visualization
Jupyter: Interactive development environment
Contributing
Fork the repository
Create a feature branch (git checkout -b feature/new-feature)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature/new-feature)
Create a Pull Request
License
This project is part of the IBM SkillsBuild program and is for educational purposes.

Contact
For questions or suggestions, please open an issue in this repository.
