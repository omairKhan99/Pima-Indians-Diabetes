
# kNN Diabetes Classifier

This project uses the k-Nearest Neighbors (kNN) algorithm to predict whether a person has diabetes based on health indicators. The objective of this project is to classify individuals as diabetic or non-diabetic using health data such as glucose levels, blood pressure, BMI, etc. The model is built using Python and the `scikit-learn` library, with data preprocessing performed through scaling and splitting the dataset into training and testing sets.

### Steps:
1. **Data Preprocessing**: Features were scaled using standardization to ensure that the kNN algorithm, which is distance-based, performs optimally. The dataset was split into training and testing sets.
2. **Model Training**: Trained a k-Nearest Neighbors classifier with `k=5` on the scaled training data.
3. **Evaluation**: The model was evaluated on the test data using metrics such as accuracy, confusion matrix, and a classification report.

## Files
- `knn_diabetes_classifier.py`: Python script for the kNN model.
- `diabetes.csv`: Dataset containing health data.

## How to Run

1. Ensure you have Python installed.
2. Install necessary dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```
   python knn_diabetes_classifier.py
   ```

## Dependencies
- pandas
- numpy
- scikit-learn








