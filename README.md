# Prediction of Mental Health Issues
This repository houses the code and resources for a machine learning project focused on predicting mental health conditions based on a comprehensive dataset. The project aims to leverage various classification models to enhance pre-diagnosis screening and contribute to a deeper understanding of mental health factors within workplace environments.

## Prerequisites

Before using this code, you should have the following installed:
- Python(>=3.7)
- Jupyter Notebook (optional, but recommended)
- Required libraries can be installed via pip:
  ```sh
  pip install pandas numpy scikit-learn matplotlib seaborn

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/mayankpujara/Prediction-of-Mental-Health-Issues.git
2. Navigate to the project directory:
   ```sh
   cd Prediction-of-Mental-Health-Issues

## Dataset

The code uses a dataset from 'Mental Health Survey Dataset.csv' containing the data entries that measures attitudes towards mental health and frequency of mental health disorders in the tech workplace. The dataset may require additional preprocessing and cleaning, as demonstrated in the code.

You can access the original dataset on Kaggle [here](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)

## Model Performance
- K Nearest Neigbour Classifier: 68.5185%
- Random Forest Classifier: 73.8095%
- Support Vector Classification Model: 70.6349%
- Decision Tree Classifier: 64.2857%
<br><br>
The Random Forest Classifier demonstrated the highest accuracy in predicting mental health conditions, showcasing the effectiveness of machine learning techniques for pre-diagnosis screening.
