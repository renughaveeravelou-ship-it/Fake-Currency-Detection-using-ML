# Fake Currency Detection using ML
A Machine Learning project that predicts whether a banknote is authentic or fake using classification algorithms. This project includes model training, API development, and deployment-ready files for real-world usage.

# Features
Banknote authenticity prediction using Machine Learning
REST API built with Flask
Trained ML model included (classifier.pkl)
Easy-to-use Python scripts
Dataset included for training and testing
Beginner-friendly project structure

# Technologies Used
Python
Flask
Scikit-learn
Pandas
NumPy
Jupyter Notebook

# Project Structure
End_to_End_Machine_Learning_Project/
│
├── app.py                      # Flask API application
├── main.py                     # Main execution file
├── Banknote.py                 # Prediction script
├── classifier.pkl              # Trained machine learning model
├── BankNote_Authentication.csv # Dataset
├── modelTraining.ipynb         # Model training notebook
├── requirements.txt            # Required Python libraries
├── pyproject.toml              # Project configuration
└── README.md                   # Project documentation
Installation

Clone the repository:
git clone <your-github-repo-link>

Move into the project folder:
cd End_to_End_Machine_Learning_Project

Install dependencies:
pip install -r requirements.txt

# Run the Project

Start the Flask application:
python app.py

The server will run on:
http://127.0.0.1:5000/

# API Example
Prediction Endpoint
POST /predict
Sample JSON Input
{
  "variance": 2.3,
  "skewness": 6.7,
  "curtosis": 3.2,
  "entropy": -1.2
}
Sample Output
{
  "prediction": "Authentic Banknote"
}

# Dataset Information

The dataset contains banknote features extracted from images:
Variance
Skewness
Curtosis
Entropy

These features are used to classify banknotes as real or fake.

# Future Improvements
Add frontend UI for prediction
Deploy using Streamlit or Render
Improve model accuracy
Add authentication system
Docker support

# Author
Renugha V

# License
This project is created for educational and learning purposes.