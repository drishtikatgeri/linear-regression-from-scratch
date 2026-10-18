# Linear Regression from Scratch (NumPy)

Made for my Essentials of AI (Core) course.

I built linear regression using only NumPy and tested it on fake house price data (price depends on size, bedrooms and age).

## What it does
- Generates 500 houses with a known price formula plus random noise
- Splits the data into train and test sets and scales the features
- Solves for the model using the **normal equation**
- Trains the same model using **gradient descent**
- Compares both using **RMSE** and **R²**

## Results
| Method | RMSE | R² |
|---|---|---|
| Normal equation | ~19,803 | 0.98 |
| Gradient descent | ~19,803 | 0.98 |

Both methods match, which means both are working correctly.

## Screenshots
<img width="887" height="496" alt="image" src="https://github.com/user-attachments/assets/1c879153-5e31-4ae7-aaa0-eebf9d411e34" />
<img width="859" height="485" alt="image" src="https://github.com/user-attachments/assets/405cea8c-48e9-437b-a655-6626598bc3c0" />


## Run it
Click the **Open in Colab** badge at the top of the notebook and run all cells. Only NumPy and Matplotlib are needed.

## What I learned
- Linear regression is just finding the best fit through the data
- Scaling features matters for gradient descent
- Two different methods can reach the same answer

## Tech
Python, NumPy, Matplotlib, Google Colab
