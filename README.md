# Diabetes_Predictor

## Overview
Diabetes_Predictor is a machine learning project that utilizes logistic regression to predict the likelihood of diabetes in individuals based on various health metrics. This repository also includes a web application that allows users to input new data points and receive predictions.

## Project Structure
The project is structured as follows:
- `data/`: Contains the dataset used for training and testing the model.
- `notebooks/`: Jupyter notebooks used for data exploration, preprocessing, and model development.
- `models/`: Saved models for prediction.
- `web_app/`: Contains the web application files.
  - `app.py`: The main Flask application.
  - `templates/`: HTML templates for the web app.
  - `static/`: Static files (CSS, JS, images) for the web app.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project documentation (this file).

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Diabetes_Predictor.git
    cd Diabetes_Predictor
    ```

2. Create a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the web application:
    ```sh
    python web_app/app.py
    ```

5. Open your browser and go to `http://127.0.0.1:5000` to access the web app.

## Usage
### Predicting Diabetes
1. Open the web application in your browser.
2. Enter the required health metrics in the provided form.
3. Click on the "Predict" button to get the prediction.

### Training the Model
If you want to train the model with new data:
1. Add your data to the `data/` directory.
2. Use the Jupyter notebooks in the `notebooks/` directory to preprocess the data and train the model.
3. Save the new model to the `models/` directory.

## Contributing
If you want to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
5. Create a pull request.

---

Feel free to reach out if you have any questions or need further assistance!
