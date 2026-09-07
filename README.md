# Hotel Booking Cancellation Prediction using ANN

## About the Project

This is a beginner Artificial Neural Network (ANN) project that predicts whether a hotel booking will be cancelled.

## Problem Statement

Can we predict whether a hotel booking will be cancelled based on booking information?

## Machine Learning Model

Artificial Neural Network (ANN)

The ANN is built using **PyTorch**.

## Inputs

The model uses two input features:

- `lead_time` — Number of days between booking and arrival
- `adr` — Average Daily Rate of the booking

## Output

- `is_canceled`
  - `0` → Booking is not cancelled
  - `1` → Booking is cancelled

## Technologies Used

- Python
- Pandas
- PyTorch
- Scikit-learn
- Google Colab

## How It Works

The project follows these steps:

1. Load the hotel booking dataset.
2. Select two input features.
3. Split the data into training and testing sets.
4. Convert the data into PyTorch tensors.
5. Build an Artificial Neural Network.
6. Train the ANN using the training data.
7. Test the model on unseen data.
8. Predict whether a booking will be cancelled.

## Project Structure

```text
hotel-booking-cancellation-ann/
│
├── hotel-booking-cancellation-ann.py
└── README.md
