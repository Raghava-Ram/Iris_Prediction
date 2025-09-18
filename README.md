# Iris Flower Prediction

This project predicts the species of an Iris flower based on its sepal and petal measurements using a machine learning model trained on the classic Iris dataset.

## Features

- Interactive web app built with Streamlit
- Predicts Iris species: Setosa, Versicolor, or Virginica
- Uses a Random Forest Classifier for robust performance

## Files

- `app.py`: Streamlit app for making predictions
- `iris_model.pkl`: Pre-trained Random Forest model
- `iris.ipynb`: Jupyter notebook for model training and export
- `README.md`: Project documentation
- `LICENSE`: MIT License

## How to Run

1. Install dependencies:
    ```sh
    pip install streamlit scikit-learn numpy joblib
    ```

2. Run the app:
    ```sh
    streamlit run app.py
    ```

3. Use the sliders to input flower measurements and click "Predict" to see the predicted species.

## Model Training

The model is trained in `iris.ipynb` using scikit-learn's RandomForestClassifier and saved with joblib.

## License

This project is licensed under the MIT