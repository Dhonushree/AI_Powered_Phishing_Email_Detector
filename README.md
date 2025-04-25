# 🛡️ AI-Powered Phishing Email Detector

A simple machine learning-based system to classify emails as **phishing** or **legitimate**, developed using Python and scikit-learn. This project is part of an academic submission for the *Computer Science Project* module at IU.

---

## 📌 Objective

To develop an intelligent email classification system using Natural Language Processing (NLP) and supervised machine learning to detect phishing emails based on their textual content.

---

## 💻 Technologies Used

- **Python 3**
- **Pandas** – data manipulation
- **Scikit-learn** – model building and evaluation
- **TF-IDF** – feature extraction from email text
- **Joblib** – model serialization

---

## 📂 Project Structure

AI_Powered_Phishing_Email_Detector/  
   ├── data/ │ └── phishing_sample.csv # Sample dataset 
   ├── model/ │ └── phishing_model.pkl # Saved ML model (generated after training) 
   ├── phishing_detector.py # Main script 
   ├── requirements.txt # List of dependencies 
   ├── README.md # Project documentation 
   └── Phase_2_Report.pdf # Draft report for submission


---

## 📥 Installation

1. **Clone the repository**

```bash
   git clone https://github.com/Dhonushree/AI_Powered_Phishing_Email_Detector.git
   cd AI_Powered_Phishing_Email_Detector

2. Install dependencies

   Make sure you have Python 3.7+ and pip installed.
   pip install -r requirements.txt

🚀 How to Run
   python phishing_detector.py

The script will:
   Load and clean the dataset
   Extract features using TF-IDF
   Train a logistic regression model
   Evaluate the model using classification metrics
   Save the trained model to the model/ folder

🧪 Sample Output
                 precision    recall  f1-score   support

   legitimate       1.00      1.00      1.00         1
     phishing       1.00      1.00      1.00         1

    accuracy                           1.00         2
Note: This output is based on a small sample. Use a larger dataset for real-world usage.

🧠 Future Improvements

   Use a real-world phishing dataset (e.g., Enron or PhishTank)
   Experiment with more advanced models (Random Forest, BERT, etc.)
   Build a web interface for user interaction
   Implement real-time email scanning

📖 Report
   This project is part of Phase 2 for the IU course "Project: Computer Science".
   You can find the project report in Phase_2_Report.pdf.

🔗 References
   scikit-learn Documentation
   UCI Machine Learning Repository
   Python Official Website

👩‍💻 Author
   Name: Dhonushree
   University: IU International University of Applied Sciences
