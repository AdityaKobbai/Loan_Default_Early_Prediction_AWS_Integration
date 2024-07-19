# Machine Learning-Based Loan Default Early Warning System

Welcome to the repository for my advanced machine learning project focused on predicting loan defaults. This project leverages a robust, scalable architecture deployed on AWS to deliver precise default predictions, helping financial institutions mitigate risks and avoid significant losses.

 src="<img width="700" alt="Screenshot 2024-07-18 at 9 10 31 PM" src="https://github.com/user-attachments/assets/19e83ee0-9100-4600-8790-302e65a1209c">

src="<img width="700" alt="Screenshot 2024-07-18 at 9 09 24 PM" src="https://github.com/user-attachments/assets/b2bdc6db-a117-4605-90cf-cd6ad0723b31">



## Project Overview

This project encompasses the full cycle of data handling, model development, and deployment, utilizing AWS cloud capabilities to enhance predictive accuracy and operational efficiency.

### Data Handling and Initial Analysis

- **Data Preprocessing:** Cleaned and structured datasets for optimal analysis.
- **Exploratory Data Analysis (EDA):** Identified key predictors and analyzed data patterns to inform effective feature engineering.

### Feature Engineering

Developed new features from existing data to improve the model's accuracy in predicting potential loan defaults.

### Model Development and Selection

- **Experimentation:** Tested various models, including Logistic Regression, Random Forest, and Gradient Boosting Machines.
- **Model Selection:** Selected the best-performing model based on accuracy, precision, recall, and F1-score.

### Application Development and Modular Programming

Implemented modular programming to enhance the maintainability and scalability of the application.
Developed a Flask web application for real-time data input and prediction output.

### Deployment on AWS

- **Containerization:** Used Docker to create a consistent deployment environment.
- **AWS Elastic Container Registry (ECR):** Stored and managed Docker images.
- **Continuous Deployment:** Integrated with GitHub Actions for automated updates and deployments via AWS Elastic Beanstalk.

### Key Features

- **Real-Time Predictions:** Users can input data and receive instant predictions.
- **High Accuracy and Precision:** Delivers reliable predictions to support financial decision-making.
- **Scalable Infrastructure:** Built on AWS to efficiently handle increasing data volumes and user demands.

### Technologies Used

- **AWS:** For deploying and managing the application.
- **Docker:** For creating isolated environments that replicate production settings.
- **Flask:** For backend development of the web application.
- **GitHub Actions:** For CI/CD, ensuring seamless updates and deployments.

## Getting Started

To get started with this project, please refer to the installation guide and follow the instructions to set up your environment.

### Installation

Detailed steps to set up the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/AdityaKobbai/Loan_Default_Early_Prediction_AWS_Integration
    ```

2. Navigate to the project directory and install the dependencies:
    ```bash
    cd Loan_Default_Early_Prediction_AWS_Integration
    pip install -r requirements.txt
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```

## Usage

After setting up the environment and running the Flask application, you can use the web interface to input data and receive predictions in real-time.
