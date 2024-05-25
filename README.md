# Breast Cancer Classifier: Improving Logistic Regression Models

This repository contains a comprehensive Jupyter notebook for building and improving a logistic regression model to classify breast cancer. The notebook leverages the Breast Cancer Wisconsin dataset and showcases multiple feature selection techniques to optimize the model's performance.

## Notebook Overview

1. **Data Loading and Preprocessing**
   - Load the Breast Cancer dataset from `sklearn.datasets`.
   - Scale the features using `MinMaxScaler` for better model convergence.

2. **Model Building and Evaluation**
   - Split the dataset into training and testing sets.
   - Build an initial logistic regression model without any feature selection.
   - Evaluate the model's performance using metrics like precision, recall, and F1 score.

3. **Feature Selection Techniques**
   - **Variance Thresholding:** Select features based on variance to reduce dimensionality.
   - **K-Best Features:** Use statistical tests to select the top k features.
   - **Sequential Forward Selection:** Iteratively add features that improve the model's performance.

4. **Model Comparison**
   - Compare the performance of different models using classification reports.
   - Visualize the results of sequential forward selection.

## Key Libraries Used
- `numpy` and `pandas` for data manipulation.
- `scikit-learn` for model building, scaling, and feature selection.
- `matplotlib` for plotting.
- `mlxtend` for sequential feature selection.

## Installation
To run the notebook, you need to have the following libraries installed:
```bash
pip install numpy pandas scikit-learn matplotlib mlxtend
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-classifier.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd breast-cancer-classifier
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook
   ```
4. Run the notebook cells to see the implementation and results.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

This repository provides a practical example of how different feature selection methods can impact the performance of a logistic regression model in a real-world classification task. Whether you're a beginner or an experienced data scientist, this notebook offers valuable insights and techniques for model improvement.
