# AccidentSurvivalChance

This project develops a machine learning model to predict the survival chances of individuals involved in accidents. The model utilizes a dataset with various accident-related parameters and applies several classification algorithms to determine survival probabilities.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting survival chances in accidents is crucial for emergency response and healthcare planning. This project aims to create a predictive model that can assess the likelihood of survival based on accident data, helping improve emergency care and resource allocation.

## Features

- **Data Preprocessing:** Cleans and prepares the dataset, handling missing values and scaling features.
- **Model Training:** Implements several machine learning models, including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM).
- **Model Evaluation:** Uses cross-validation and metrics such as accuracy, precision, recall, and F1-score to evaluate the performance of different models.
- **Visualization:** Provides visualizations to compare model performance and understand feature importance.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kabirkohli123/accident-survival-prediction.git
   cd accident-survival-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter notebook to execute the model training and evaluation:
   ```bash
   jupyter notebook AccidentSurvivalChancePredict.ipynb
   ```

2. Follow the steps in the notebook to preprocess data, train models, and evaluate performance.

## Project Structure

```
accident-survival-prediction/
├── AccidentSurvivalChancePredict.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── accident_data.csv
```

- **AccidentSurvivalChancePredict.ipynb:** Jupyter notebook with the full implementation of the project.
- **README.md:** Project documentation.
- **requirements.txt:** List of dependencies.
- **data/accident_data.csv:** Dataset containing accident-related parameters for survival prediction.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or create a pull request. Follow the contribution guidelines in `CONTRIBUTING.md`.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Thank you for using the Accident Survival Chance Prediction project! If you have any questions or need further assistance, please feel free to contact us.

Happy coding!
