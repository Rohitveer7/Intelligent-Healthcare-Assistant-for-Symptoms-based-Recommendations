# Intelligent Healthcare Assistant for Symptoms based Recommendations

# Introducation

### This project is an Intelligent Healthcare Assistant that predicts diseases based on the user-input symptoms using machine learning and deep learning models. It provides detailed recommendations including:

- Disease Description
- Medications
- Diets Plan
- Workout Suggestions

## Table of Contents

- [Project Overview](#project-overview)
- [Feature](#features)
- [Project Structure](#project-structure)
- [Datasets](#datasets)
- [Technology Used](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Contact](#contact)

# Project Overview
This project is a machine learning and deep learning-based system for predicting diseases based on user-input symptoms. It provides personalized recommendations including disease descriptions, precautions, medications, diets, and workout suggestions. The system includes multiple disease prediction and single disease prediction capabilities.

# Features
1. Symptom-Based Disease Prediction
   - Accepts single or multiple symptoms from the user.
   - Predicts one or more potential diseases.

2. Comprehensive Recommendations
   - Provides a detailed description of the predicted disease.
   - Suggests relevant precautions, medications, diet plans, and workouts.

3. Interactive Web Interface
   - A user-friendly interface with categorized symptoms for easy selection.
   - Colorful and professional design for enhanced user experience.

4. Machine Learning Models
   - Includes algorithms such as SVC, RandomForest, GradientBoosting, KNeighbors, and Gaussian.
   - A stacked model for improved accuracy.
   - Deep learning model with early stopping and visualization of training metrics.

5. Dynamic Dataset Integration
   - Uses multiple datasets for symptoms, disease descriptions, precautions, medications, diets, and workouts.

## Project Structure

    .
    project-folder/
    │
    ├── datasets/                   # All datasets used for predictions
    |       ├── diets.csv
    │       ├── medications.csv
    │       ├── precautions.csv
    │       ├── symptom-severity.csv
    │       ├── symptom_df.csv
    │       ├── training.csv
    │       └── workouts.csv
    |
    ├── static/                 # Static files for the web interface 
    │        ├── css/
    │        └── js/
    |
    ├── templates/             # HTML templates
    │   └── index.html
    |
    ├── ml/                   # Machine learning and deep learning code
    │   ├── model.py          # ML model training and prediction
    │   ├── preprocess.py     # Data preprocessing utilities
    │   └── helper.py         # Helper functions
    ├── app.py                # Flask/Django/FastAPI app for deployment
    └── README.md

## Datasets

The project includes the following datasets:

- description.csv: Contains disease descriptions.
- diets.csv: Provides diet recommendations for diseases.
- medications.csv: Lists medications for diseases.
- precautions.csv: Details precautions for diseases.
- symptom-severity.csv: Maps symptoms to severity levels.
- symptom_df.csv: Symptom details.
- training.csv: Training data for ML models.
- workouts.csv: Suggested workouts for diseases.

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Python, Flask/FastAPI
- Machine Learning: Scikit-learn, TensorFlow/Keras
- Data Visualization: Matplotlib, Seaborn
  
## Features

- *Disease Prediction*: Predicts diseases based on input symptoms using ML/DL models.
- *Personalized Recommendations*: Provides detailed descriptions, precautions, medications, diets, and workout plans.
- *Single and Multiple Disease Prediction*: Supports both single and multiple disease predictions.
- *Interactive Web Interface*: User-friendly interface for inputting symptoms and receiving recommendations.

## Installation

1. Clone the repository:
   ```bash  
   git clone https://github.com/your-username/Intelligent-Healthcare-Assistant.git  
   cd Intelligent-Healthcare-Assistant  
   
2. Install the required dependencies:
   ```bash
    pip install -r requirements.txt  
   
3. Run the Flask application:
   ```bash
    python app.py 
   
4. Open your browser and navigate to [http://127.0.0.1:5000.](http://127.0.0.1:5000)

## Usage

1. Launch the web application.
2. Input your symptoms in the form provided.
3. Get recommendations, including:
     - Medications
     - Precautions
     - Diet plans
     - Workout routines

## Contributors 
Contributions are welcome! Fork the repository, create a branch, and submit your pull request.

## Contact
- Name: Rahul Rajshekhar Yadwad
- Email: [rahulyadwad1718@gmail.com]
