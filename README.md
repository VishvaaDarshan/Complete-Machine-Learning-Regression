# Student Exam Performance Prediction

This project aims to predict student exam scores based on various features such as gender, race/ethnicity, parental level of education, lunch type, test preparation course, and scores in writing and reading.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Logging and Exception Handling](#logging-and-exception-handling)
- [License](#license)

## Project Description
The Student Exam Performance Prediction project is an end-to-end machine learning project that predicts student exam scores. The project includes data ingestion, data preprocessing, model training, evaluation, and prediction. The project is structured to follow best practices for code organization, logging, and exception handling.

## Dataset
The dataset used in this project contains information about students and their exam scores. The dataset includes the following columns:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Writing Score
- Reading Score
- Math Score (target variable)

The dataset is provided in a CSV file named `stud.csv`.

## Project Structure
The project is organized into the following directories and files:

## Setup Instructions
Follow these steps to set up the project on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/student-exam-performance-prediction.git
    cd student-exam-performance-prediction
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - For Windows:
        ```bash
        venv\Scripts\activate
        ```
    - For macOS and Linux:
        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Data Ingestion**: Run the data ingestion script to load the data from the CSV file.
    ```bash
    python data_ingestion/data_ingestion.py
    ```

2. **Data Preprocessing**: Run the data preprocessing script to clean and preprocess the data.
    ```bash
    python data_preprocessing/data_preprocessing.py
    ```

3. **Model Training**: Train the machine learning model using the training script.
    ```bash
    python model_training/model_training.py
    ```

4. **Prediction**: Make predictions on new data using the prediction script.
    ```bash
    python prediction/prediction.py
    ```

## Model Training
The model training script (`model_training/model_training.py`) handles the training of the machine learning model. It reads the preprocessed data, splits it into training and testing sets, trains the model, and evaluates its performance.

## Prediction
The prediction script (`prediction/prediction.py`) uses the trained model to make predictions on new data. Ensure that the model is trained before running the prediction script.

## Logging and Exception Handling
The project includes robust logging and exception handling mechanisms. Logs are written to files in the `logs` directory, and custom exceptions are defined in the `exceptions/custom_exceptions.py` file.


