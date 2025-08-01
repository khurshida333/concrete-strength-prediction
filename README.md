# Concrete Strength Prediction vs Rebound Hammer

This script trains a Random Forest regression model to predict concrete compressive strength (`fc_prime`) using rebound hammer readings and mix proportions, 
then compares its accuracy to the raw rebound hammer value.

## Requirements

- Python 3.8+  
- Packages (can install via):
  ```sh
  pip install pandas numpy scikit-learn matplotlib openpyxl
