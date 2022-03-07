# Covid Risk Prediction WebApp ![GitHub language count](https://img.shields.io/github/languages/count/YogeshRajgure/Covid-Risk-Prediction-Webapp?color=green)

## Title: Predicting high risk COVID-19 patients.

- The objective of this project is to predict if a COVID-19 patient will have a high risk of death in near future.
- The machine learning model is based on Random Forest Classifier, which takes initial health data of the patient as input.
- The project is a web app built using python flask and gunicorn.

# How to run this app on your local machine:
**Prerequisites:**
- Python >=3.8.3

1. **PROJECT SETUP**  
    If you don’t have this project.
    - Go to the desired location where you want to save the project.
    ```cmd
    cd <your_desired_path>
    ```
    - Clone the project from the repo.
    ```cmd
    git clone https://www.github.com/YogeshRajgure/Covid-Risk-Prediction-Webapp
    cd Covid-Risk -Prediction-Webapp/
    ```

    If you have this project already.
    - Go to the project’s location.
    ```cmd
    cd <your_project’s_path>
    ```
    - Pull the project from the repo.
    ```cmd
    git pull origin
    ```

2. **PYTHON VIRTUAL ENVIRONMENT SETUP**  
    - Create a python virtual environment.
    ```cmd
    python -m venv venv
    ```
    - Activate the virtual environment.
    ```cmd
    source venv/scripts/activate
    ```

    You need to activate the virtual environment every time you wish to run the app.

3. **INSTALL DEPENDENCIES**  
    ```cmd
    pip install -r requirements.txt
    ```

4. **RUN THE APP**  
    Run this command to run the app.
    ```cmd
    python app.py
    ```

