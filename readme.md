
# Customer Churn Classification using Artificial Neural Network (ANN)

This project focuses on predicting customer churn using an Artificial Neural Network (ANN). It includes data preprocessing, model training, and a Streamlit web application for making predictions.

## Project Structure

- `experiments.ipynb`: Jupyter notebook containing the data preprocessing, model training, and evaluation steps.
- `prediction.ipynb`: Jupyter notebook for making predictions using the trained model.
- `app.py`: Streamlit application for user-friendly predictions.
- `model.h5`: Saved ANN model.
- `label_encoder_gender.pkl`: Pickle file for gender label encoder.
- `onehot_encoder_geo.pkl`: Pickle file for geography one-hot encoder.
- `scaler.pkl`: Pickle file for feature scaler.
- `requirements.txt`: all the requirements mentioned

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/kshitijkumrawat20/CustomerChurnClassificationByANNproject.git
   cd <repository-name>
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

### Data Preprocessing and Model Training

Run the `experiments.ipynb` notebook to preprocess the data, train the ANN model, and save the necessary files.

### Streamlit Web Application

Run the Streamlit app:

```
streamlit run app.py
```

Access the web application at: [https://customerchurnclassificationbyannproject-srnsufutxef6xcy8htizbq.streamlit.app/](https://customerchurnclassificationbyannproject-srnsufutxef6xcy8htizbq.streamlit.app/)

## Model Details

- Architecture: Artificial Neural Network (ANN)
- Input Features: CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary
- Output: Binary classification (Churn / No Churn)

## Files Description

- `experiments.ipynb`: Contains data loading, preprocessing, model creation, training, and evaluation.
- `prediction.py`: Demonstrates how to use the trained model for making predictions.
- `app.py`: Streamlit application for user-friendly predictions.
- `model.h5`: Saved Keras model.
- `*.pkl`: Pickle files for encoders and scaler.

## Dependencies

- TensorFlow
- Scikit-learn
- Pandas
- NumPy
- Streamlit

For a complete list of dependencies, refer to the `requirements.txt` file.

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes and commit them
4. Push to your fork and submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```

This README provides an overview of your project, including its structure, setup instructions, usage guidelines, and other relevant information. You may want to adjust some details based on your specific project setup or add more sections as needed.
