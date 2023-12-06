# Anemia-Detection
The Anemia Detection project is a web application developed using Flask, HTML, CSS, and JavaScript. The goal of the project is to predict whether an individual has anemia or not based on parameters from a Complete Blood Count (CBC) report. The parameters used for prediction include haemoglobin, mean corpuscular hemoglobin concentration (MCHC), mean corpuscular volume (MCV), and mean corpuscular hemoglobin (MCH).

The machine learning model employed in this project is a DecisionTreeClassifier. Random Forest Classifier and Logistic Regression were initially considered and tested for accuracy, but the DecisionTreeClassifier was ultimately chosen for the final model.

## Features

* Web-based user interface for easy interaction.
* Predicts anemia based on CBC parameters.
* Utilizes a DecisionTreeClassifier for accurate predictions.

## Technologies Used

* HTML, CSS, JS: for building the front-end
* Flask: A lightweight web framework for building the backend.

## Getting Started

To run the Anemia Detection project locally, follow these steps:

* Clone the repository:
```git clone https://github.com/your-username/anemia-detection.git```

* Install the required dependencies:
```pip install -r requirements.txt```

* Run the Flask application:
```python app.py```

* Open your web browser and navigate to http://localhost:5000 to use the Anemia Detection application.

