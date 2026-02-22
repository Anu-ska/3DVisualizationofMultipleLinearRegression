# 3DVisualizationofMultipleLinearRegression
This project demonstrates Multiple Linear Regression using two features from the California Housing dataset and visualizes the regression plane in 3D.
The goal of this project is to:
1. Train a Multiple Linear Regression model
2. Use two features:
  - MedInc (Median Income)
  - AveRooms (Average Number of Rooms)
3. Predict house prices
4. Visualize:
  - Actual data points (3D scatter)
  - Regression plane (best-fit surface)

📂 Dataset

The dataset used is:
  - California Housing Dataset
  - Loaded using fetch_california_housing() from sklearn

Target variable:
   - Median House Value

🧠 Machine Learning Model

Model used:
 - LinearRegression() from sklearn

The mathematical model : 𝑦=𝑏0+𝑏1𝑥1+𝑏2𝑥2
Where:
 - x1 = Median Income
 - x2 = Average Roomss
 - y = House Price
The model finds the best-fitting plane by minimizing Mean Squared Error.

📊 3D Visualization

The visualization includes:

🔵 Blue points → Actual house prices
🔴 Red surface → Regression plane

Axes:

X-axis → Median Income
Y-axis → Average Rooms
Z-axis → House Price

🛠️ Technologies Used

 - Python
 - NumPy
 - Pandas
 - Matplotlib
 - Scikit-learn

▶️ How to Run the Project
1️⃣ Install Required Libraries

   pip install numpy pandas matplotlib scikit-learn
    
2️⃣ Run the Script

python your_script_name.py


📸 Output
 - The program generates a 3D plot showing:
 - Real housing data points
 - The best-fit regression plane
 - This helps visually understand how multiple linear regression fits a plane in 3D space.
