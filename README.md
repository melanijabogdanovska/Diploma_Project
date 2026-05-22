# Electricity Consumption Forecasting using Neural Networks

This project presents a comparison between different neural network architectures for monthly electricity consumption forecasting.

The implemented models are:

* Multi-Layer Perceptron (MLP)
* Convolutional Neural Network (CNN)
* Long Short-Term Memory (LSTM)

The project is developed in Python using TensorFlow/Keras inside Jupyter Notebook.

## Dataset

The dataset contains monthly electricity consumption values.

Due to the limited size of the dataset, simpler neural network architectures achieve better performance compared to more complex sequence models.

## Project Workflow

* Data preprocessing
* Scaling using MinMaxScaler
* Sliding window sequence generation
* Training / validation split
* Model training with EarlyStopping
* Validation evaluation
* Final forecasting on test period

## Technologies

* Python
* Jupyter Notebook
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Results

The MLP model achieves the best overall performance on the available dataset.

CNN and LSTM models show higher prediction errors due to the limited amount of sequential training data required for learning long-term temporal dependencies.

## Repository Structure

* `finalna_diplomna.ipynb` — complete notebook implementation
* training, validation and testing workflow
* visualization of forecasting results
* comparison of model metrics

## Notebook

Full notebook implementation:

[Open Notebook](https://github.com/melanijabogdanovska/Diploma_Project/blob/main/finalna_diplomna.ipynb?utm_source=chatgpt.com)
