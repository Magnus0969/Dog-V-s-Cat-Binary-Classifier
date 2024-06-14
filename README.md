# DOG vs CAT Image Classification

This project involves building a Convolutional Neural Network (CNN) using Keras to classify images of dogs and cats. The model is trained on a dataset of images and then evaluated on a test set to determine its accuracy in distinguishing between the two classes.

## Dataset

The dataset used for this project consists of images of dogs and cats. The images are preprocessed and stored in CSV files which are loaded and used to train and test the model.

- `input.csv`: Training set images
- `labels.csv`: Training set labels
- `input_test.csv`: Test set images
- `labels_test.csv`: Test set labels

## Project Structure

- `DOGvsCAT.ipynb`: Jupyter notebook containing the code for data preprocessing, model building, training, and evaluation.

## Requirements

To run the notebook, you need the following libraries installed:

- numpy
- pandas
- tensorflow (Keras)

You can install the required libraries using pip:

```bash
pip install numpy pandas tensorflow
