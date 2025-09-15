# NewsVerifier-ML

A Machine Learning project that detects whether a given news article is Fake or Real using Natural Language Processing (NLP) techniques and classification models.



# Features
- Preprocessing of textual news data  
- Feature extraction using TF-IDF  
- Classification with trained ML models  
- Simple prediction script for testing news text  

# Project Structure
├── classifier.py - Model training script
├── prediction.py  - Run predictions on custom news text
├── train.csv  - Training dataset
├── valid.csv  - Validation dataset
├── test.csv  - Test dataset
├── final_model.sav  - Trained model (pickle file)
├── final-fnd.ipynb  - Jupyter Notebook (experiments)
├── DataPrep.py  -Data preprocessing
├── FeatureSelection.py  - Feature selection methods
├── README.md  - Project documentation


#  Installation & Setup  
Getting started with NewsVerifier-ML is straightforward.  

# Prerequisites  
- Python 3.8+  
- pip (Python package manager)  
- Virtual environment tool (recommended)  

# Quickstart  
Clone the repository and navigate into it:  

 git clone https://github.com/Veda55/NewsVerifier-ML.git
 cd NewsVerifier-ML

# Set up the environment:
 python -m venv venv

# Activate it
source venv/bin/activate     # Mac/Linux  
venv\Scripts\activate        # Windows

# Install the required dependencies:
  pip install -r requirements.txt

#Run the prediction script:
  python prediction.py

# Results  
The trained model achieves strong performance on benchmark datasets.  
- Logistic Regression Accuracy: 89%
- Naive Bayes Accuracy: 84% 
- SVM Accuracy: 91%

Example:  
  Input: "A new vaccine has been approved"
  Output:  REAL NEWS

# Future Improvements  
- Experiment with deep learning models (LSTMs, Transformers, BERT)  
- Deploy as a web app using Flask/Streamlit  
- Extend support for multilingual news detection  
- Improve explainability using SHAP/LIME  



