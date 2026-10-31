# Human Activity Recognition

A machine learning project that classifies human activities from smartphone sensor data using a neural network built with TensorFlow and Keras.

## Project contents

- `Human Activity Recognition.ipynb` — notebook for loading the data, preparing features, training models, and evaluating results.
- `Data sets/train.csv` — training dataset.
- `Data sets/test.csv` — test dataset.

The notebook expects the six activity classes to be provided in the `Activity` column. It uses the other sensor columns as input features.

## Requirements

- Python 3.10 or 3.11
- Jupyter Notebook
- TensorFlow
- Keras Tuner
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Seaborn

Install the Python packages with:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow keras-tuner jupyter
