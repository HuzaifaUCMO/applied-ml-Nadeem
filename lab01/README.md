# Housing Price Prediction using Regression

## Introduction
This project applies **regression modeling** to predict housing prices based on various features such as median income and average rooms per household. The dataset used is the **California Housing Prices Dataset** from Scikit-Learn.

## Project Overview
The main objectives of this project are:
- Load and explore the dataset
- Visualize feature distributions
- Select relevant features for modeling
- Train a **Linear Regression** model
- Evaluate model performance using **R², MAE, and RMSE**

## Dataset
We use the **California Housing Prices Dataset** available in `sklearn.datasets`. This dataset contains:
- **Features:** Median income, number of rooms, latitude, longitude, and more.
- **Target Variable:** Median house price in a district.

## Installation
To set up the project, follow these steps:
1. **Clone the Repository**:
   ```sh
   git clone <repository-link>
   cd <project-folder>
   ```
2. **Create a Virtual Environment (Optional but Recommended):**
   ```sh
   python -m venv .venv
   source .venv/bin/activate  # On Windows, use .venv\Scripts\activate
   ```
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Running the Notebook
1. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Open `ml01.ipynb` and run the cells step by step.

## Project Structure
```
├── ml01.ipynb        # Jupyter Notebook with code and analysis
├── requirements.txt  # List of dependencies
├── README.md         # Project documentation
└── .venv/            # Virtual environment (optional)
```

## Model Performance
The trained **Linear Regression Model** is evaluated using:
- **R² Score:** Measures how well the model explains variability.
- **Mean Absolute Error (MAE):** Average absolute differences between actual and predicted values.
- **Root Mean Squared Error (RMSE):** Measures prediction error magnitude.

## Results
- The **R² Score** indicates how well the model fits the data.
- **Lower RMSE and MAE** suggest better performance.

## Future Improvements
- Experimenting with **additional regression models** (e.g., Decision Trees, Random Forests).
- Feature engineering to improve predictive performance.
- Hyperparameter tuning for better optimization.

## Author
**Huzaifa Nadeem**

## License
This project is for educational purposes. Modify and distribute as needed!

---
For any issues, feel free to reach out!



