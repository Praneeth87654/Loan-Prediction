# Loan Prediction

## Overview  
The **Loan Prediction System** is a machine learning-based project designed to predict whether a loan application will be approved or rejected based on applicant details. The project utilizes advanced data preprocessing techniques, multiple classification algorithms, and a Flask-based web interface for user interaction.  

## Key Features  
- **Balanced Dataset**: Used SMOTETomek to handle class imbalance.
- **Multiple Models**: Implemented Random Forest, Decision Tree, and XGBoost for predictions.
- **Hyperparameter Tuning**: Optimized model performance using Grid Search and Random Search.
- **User-Friendly Interface**: Developed a Flask web application for collecting user inputs and displaying predictions.
- **High Accuracy**: Achieved reliable predictions through thorough evaluation and fine-tuning.

## Project Workflow  
1. **Data Preprocessing**:  
   - Handle missing values.  
   - Encode categorical variables.  
   - Balance the dataset using SMOTETomek.  

2. **Model Development**:  
   - Random Forest  
   - Decision Tree  
   - XGBoost  
   - Compare model performance and select the best-performing model.  

3. **Model Evaluation**:  
   - Use metrics like accuracy, precision, recall, and F1-score.  

4. **Web Application**:  
   - Deploy the selected model using Flask.  
   - Build an interactive UI for input data collection.  

## Installation  

### Prerequisites  
Ensure you have the following installed:  
- Python 3.8+  
- Flask  
- Scikit-learn  
- XGBoost  
- SMOTETomek  
- Pandas  
- NumPy  
- Matplotlib  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/loan-prediction.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd loan-prediction  
   ```  

3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Run the Flask application:  
   ```bash  
   python app.py  
   ```  

5. Open your browser and visit:  
   ```  
   http://127.0.0.1:5000/  
   ```  


