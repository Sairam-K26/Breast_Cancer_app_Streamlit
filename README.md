# Breast_Cancer_app_Streamlit
# Breast Cancer Prediction App

This Streamlit app allows users to predict whether a breast cancer case is benign or malignant based on user-provided input. The app utilizes machine learning techniques to make predictions using a breast cancer dataset.



## Features

- Interactive user interface for inputting feature values.
- Displays prediction results as benign (0) or malignant (1).
- Provides warnings for invalid inputs.
- Utilizes a support vector machine (SVM) classifier trained on relevant features.
- Visual representation of the breast cancer image.

## Installation

Clone or download this repository.

git clone https://github.com/your-username/breast-cancer-prediction-app.git
cd breast-cancer-prediction-app

Create a virtual environment (optional but recommended).

python -m venv venv
source venv/bin/activate  

Run the Streamlit app.

Copy code
```streamlit run app.py```

Interact with the app through your web browser.
Enter numerical values for the selected features in the sidebar.
The app will display a prediction (benign or malignant) based on the input.

**Dependencies**

streamlit
numpy
scikit-learn
Pillow (PIL)

**Data Source**

The breast cancer dataset used in this app is from the scikit-learn library's load_breast_cancer function.


