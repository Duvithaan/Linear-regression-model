# Simple Linear Regression Model

This project demonstrates a basic implementation of Linear Regression from scratch using Python. It predicts a student's score based on the number of hours studied, applying **gradient descent** to minimize error and fit a line to the data.

## Project Structure

- `Linear_regression_model.ipynb` — Main Jupyter Notebook that:
  - Reads and uses a custom dataset
  - Performs gradient descent manually
  - Plots the results
  - Tracks progress over epochs


## Features

- Implements **Linear Regression** without using libraries like `scikit-learn`
- Uses custom CSV or manually generated data
- Visualizes:
  - Raw data points
  - Best-fit regression line
- Logs training process (Epoch count)

##  Technologies Used

- Python
- `pandas` — for handling data
- `matplotlib` — for plotting
- Core Python logic for gradient descent

##  Concepts Covered

- Linear Regression
- Gradient Descent
- Cost Minimization
- Epoch-based Training
- Data Visualization


##  How to Run

1. Clone this repository or download the `.ipynb` file.
2. Open it in **Jupyter Notebook**, **Google Colab**, or **VS Code with Jupyter Extension**.
3. Run the cells one by one.
4. Modify the dataset section to input your own data if needed.


## Example Output

- The notebook will display:
  - The training log: `Epoch: 0`, `Epoch: 50`, etc.
  - Final values of slope (`m`) and intercept (`b`)
  - A scatter plot with a red regression line

##  Future Improvements

- Add error metrics like MSE, RMSE, R²
- Normalize/scale data
- Extend to multiple linear regression


