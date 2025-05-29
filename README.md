# Stock-Risk-Predictor-Machine-Learning
# Heart Disease Predictor

This repository contains a Jupyter Notebook designed to predict heart disease using a machine learning model. The model uses a dataset of patient health metrics to classify the likelihood of heart disease.

## Features

* Data loading and exploration
* Preprocessing of the dataset
* Machine learning model training and evaluation
* Accuracy assessment

## Requirements

To run this notebook, you need the following packages installed:

* Python 3.x
* `numpy`
* `pandas`
* `scikit-learn`

You can install the required packages using:

```bash
pip install numpy pandas scikit-learn
```

## Dataset

The dataset used in this project contains health-related attributes and the target variable `target`, which indicates the presence of heart disease:

* **age**: Age of the patient
* **sex**: Gender (1 = male, 0 = female)
* **cp**: Chest pain type (categorical)
* **trestbps**: Resting blood pressure (in mm Hg)
* **chol**: Serum cholesterol (in mg/dl)
* **fbs**: Fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
* **restecg**: Resting electrocardiographic results (categorical)
* **thalach**: Maximum heart rate achieved
* **exang**: Exercise-induced angina (1 = yes; 0 = no)
* **oldpeak**: ST depression induced by exercise relative to rest
* **slope**: Slope of the peak exercise ST segment (categorical)
* **ca**: Number of major vessels colored by fluoroscopy
* **thal**: Thalassemia (categorical)
* **target**: Target variable (1 = presence of heart disease, 0 = absence)

## Workflow

1. **Data Import and Exploration**: Load the dataset and perform an initial review using methods like `.head()` and `.tail()`.
2. **Data Preprocessing**: Prepare the data by handling missing values, normalizing features, and splitting it into training and testing sets.
3. **Model Training**: Use `LogisticRegression` from scikit-learn to train the model.
4. **Evaluation**: Evaluate the model's performance using accuracy metrics.

## Usage

1. Clone this repository.

   ```bash
   git clone https://github.com/your-repo/heart-disease-predictor.git
   cd heart-disease-predictor
   ```

2. Open the Jupyter Notebook in your environment:

   ```bash
   jupyter notebook Heart_disease_predictor.ipynb
   ```

3. Follow the cells in sequence to execute the workflow.

## Results

The model's accuracy is calculated and displayed at the end of the notebook. Modify the notebook to improve accuracy by experimenting with feature selection, model parameters, or alternate algorithms.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the Harshith
