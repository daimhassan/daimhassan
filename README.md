# Import necessary libraries
import numpy as np
from sklearn.linear_model import LinearRegression
import matplotlib.pyplot as plt

# Generate a small dataset
np.random.seed(42)
X = 2 * np.random.rand(100, 1)
y = 4 + 3 * X + np.random.randn(100, 1)

# Create and fit the linear regression model
model = LinearRegression()
model.fit(X, y)

# Make predictions on new data points
X_new = np.array([[0], [2]])
y_pred = model.predict(X_new)

# Plot the original data and the linear regression line
plt.scatter(X, y, label='Original data')
plt.plot(X_new, y_pred, 'r-', label='Linear regression line')
plt.xlabel('X')
plt.ylabel('y')
plt.legend()
plt.show()- 👋 Hi, I’m @daimhassan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
daimhassan/daimhassan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
