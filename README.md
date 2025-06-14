# Gradient Descent: Manual vs TensorFlow Implementation

This project compares a manual implementation of gradient descent in Python (using NumPy) with TensorFlow’s built-in optimization.

It aims to help learners understand how gradient descent works behind the scenes and how frameworks simplify the process.

## Files included

- `gradient_descent_tensorflow_vs_python.py`: Main script with both implementations.
- `requirements.txt`: Required Python packages.
- `README.md`: This file.

## How to run

1. Install dependencies:  
   `pip install -r requirements.txt`

2. Run the script:  
   `python gradient_descent_tensorflow_vs_python.py`

## Expected output

- Loss values printed during training epochs.
- Plots showing loss over epochs and predicted vs actual values.

## Notes

- Currently uses a small number of epochs and basic learning rate.
- Input features are not normalized yet.

## TODO

- Normalize input features.
- Increase number of epochs.
- Add comparisons with other optimization methods.
