# Credit Card Fraud Detection

This project uses machine learning to detect fraudulent transactions in credit card data.

Dataset link: [mlg-ulb/creditcardfraud/code](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code)

## Project Structure

The main code is in the Jupyter notebook [src/data_preparations.ipynb](src/data_preparations.ipynb).

## Data Preparation

The data is preprocessed and split into training and testing sets. The data is then saved to a CSV file for later use.

## Model Training

A Transformer Autoencoder model is trained using PyTorch. The model is trained using the Contrastive Loss function.

## Model Evaluation

The model's performance is evaluated using the test set. The ROC-AUC score is calculated to measure the model's ability to distinguish between fraudulent and non-fraudulent transactions.

## Usage

To run the project, open the Jupyter notebook and execute the cells in order.

## Dependencies

This project requires the following Python libraries:

- pandas
- numpy
- sklearn
- torch
- imblearn

## License

This project is open source, under the MIT license.
