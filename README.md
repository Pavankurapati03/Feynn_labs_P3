# Heart Disease Prediction Project

Welcome to the Heart Disease Prediction Project! This project utilizes machine learning to predict the likelihood of an individual developing heart disease based on their demographic, lifestyle, and clinical attributes.

## Overview

The goal of this project is to create a predictive model for heart disease using data collected from the Behavioral Risk Factor Surveillance System (BRFSS) conducted by the CDC. The project involves data preprocessing, feature engineering, and model development using various algorithms. A web application prototype was built using Streamlit to provide an intuitive interface for users to input their health information and receive predictions regarding their risk of heart disease.

## Features

- **Machine Learning Model**: Logistic regression model trained on the BRFSS dataset to predict heart disease.
- **Web Application**: Streamlit-based app that allows users to input their health information and receive risk assessments.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature engineering to optimize model performance.
- **Model Evaluation**: Experimentation with different algorithms and evaluation metrics to select the most suitable model.

## Prerequisites

- Python 3.x
- Required libraries: Streamlit, scikit-learn, numpy, pandas

You can install the required libraries using the following command:

```
pip install -r requirements.txt
```

## How to Run the Application

1. Clone this repository to your local machine:

    ```
    git clone https://github.com/yourusername/heart-disease-prediction.git
    ```

2. Navigate to the project directory:

    ```
    cd heart-disease-prediction
    ```

3. Run the Streamlit application:

    ```
    streamlit run app.py
    ```

4. Open your browser and navigate to the URL provided in the terminal (usually `http://localhost:8501/`) to access the application.

## How to Deploy the Model in Streamlit Cloud

Streamlit Cloud allows you to easily deploy your Streamlit applications and share them with the world. To deploy the heart disease prediction model in Streamlit Cloud, follow these steps:

1. **Create a GitHub Repository**: If you haven't already, create a GitHub repository for your project and push your code to it.

2. **Sign Up for Streamlit Cloud**: Go to [Streamlit Cloud](https://streamlit.io/cloud/) and sign up for an account.

3. **Create a New App**: Once you're logged in, create a new app on Streamlit Cloud. You will need to connect your GitHub account.

4. **Choose Your Repository**: Select the repository containing your project code, and then choose the branch you want to deploy from.

5. **Configure the App**: Streamlit Cloud will automatically detect the `app.py` file as your main application file. You may configure any other settings as needed.

6. **Deploy the App**: Once your app is set up, click the "Deploy" button to deploy the application.

7. **Access the App**: After the deployment process is complete, you will be provided with a URL to access your deployed app.

Streamlit Cloud handles server management and scaling for you, making it easy to deploy and share your application with others.

## Data

The data used in this project was sourced from Kaggle. It consists of survey responses from the BRFSS 2015 dataset, containing health-related risk behaviors and chronic health conditions.

## Contributing

Contributions, issues, and feature requests are welcome! 


## Acknowledgements

- Data sourced from [Kaggle](https://www.kaggle.com/).
- The Streamlit and scikit-learn libraries were instrumental in developing this project.
