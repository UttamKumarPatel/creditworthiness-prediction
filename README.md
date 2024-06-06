# 💳 Creditworthiness Prediction using Random Forest 🌲

This repository contains code and resources for predicting the creditworthiness of individuals based on various financial attributes using a Random Forest ensemble method. The project aims to classify individuals as good or bad credit risks, helping financial institutions make informed lending decisions.

## Project Overview

### Objectives 🎯
- **Predict Creditworthiness**: Classify individuals as either good or bad credit risks.
- **Utilize Random Forest**: Leverage the Random Forest ensemble method for robust and accurate predictions.
- **Preprocess Data**: Implement data preprocessing techniques to handle both numerical and categorical data.

### Dataset 📊
The dataset used in this project is the German Credit Data, which includes various financial attributes of individuals along with their credit risk labels. The data consists of both numerical and categorical features.

### Features 🔍
- **Account Balance**: Numeric
- **Duration**: Numeric
- **Credit Amount**: Numeric
- **Purpose**: Categorical
- **Employment**: Categorical
- **Personal Status and Sex**: Categorical
- **Other attributes**: Various numerical and categorical features

### Target Variable 🎯
- **Credit Risk**:
  - `1`: Good Credit Risk
  - `2`: Bad Credit Risk

## Project Structure 🗂
- **data/**: Contains the dataset files.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and model development.
- **src/**: Source code for data preprocessing, model training, and evaluation.
- **README.md**: Project overview and setup instructions.

  ### Prerequisites 📋
- Python 3.6 or higher
- Required Python packages (listed in `requirements.txt`)

### Installation 🚀
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/creditworthiness-prediction.git
    cd creditworthiness-prediction
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install required packages**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage 📈

### Data Preprocessing ⚙️
The dataset includes both numerical and categorical features. Preprocessing steps include:
- **Standardizing Numerical Features**: Using `StandardScaler`.
- **Encoding Categorical Features**: Using `OneHotEncoder`.

### Model Training and Evaluation 🧠
The Random Forest classifier is trained using the preprocessed training data and evaluated on the test data.

Evaluation Metrics 📊
The model is evaluated using various metrics, including accuracy, precision, recall, and F1-score.

# Project Name

## Evaluation Metrics 📊
The model is evaluated using various metrics, including accuracy, precision, recall, and F1-score.

## Contributing 🤝
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License 📄
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements 🙏
- scikit-learn(https://scikit-learn.org/)
- German Credit Data(https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
