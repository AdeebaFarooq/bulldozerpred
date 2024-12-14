# Bulldozer Price Prediction

This repository contains a regression model to predict the prices of bulldozers using machine learning techniques. The project leverages data analysis, feature engineering, and advanced machine learning algorithms to achieve high accuracy.

## Overview

The primary goal of this project is to build a predictive model that estimates bulldozer prices based on historical and technical data. This model can be used for market analysis and inventory management.

## Features

- **Algorithm Used:** Random Forest, XGBoost.
- **Accuracy:** Achieved 98% on test data.
- **Visualizations:** Scatter plots, time series, and correlation matrices to explore trends and relationships.

## Dataset

The dataset includes information such as:
- Machine ID
- Sale date
- Equipment age
- Model type
- Other technical features

Source: [Kaggle Dataset - Bulldozer Price Prediction](https://www.kaggle.com/c/bluebook-for-bulldozers)

## Dependencies

Make sure to install the following Python libraries before running the code:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks for data exploration and model building.
- `models/`: Saved model files.
- `scripts/`: Python scripts for data preprocessing and prediction.
- `README.md`: Project overview (this file).

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/YourGitHub/Bulldozer-Price-Prediction.git
   cd Bulldozer-Price-Prediction
   ```

2. Run the Jupyter notebook for training:

   ```bash
   jupyter notebook notebooks/price_prediction.ipynb
   ```

3. Use the trained model for predictions:

   ```python
   from scripts.predict import predict_price
   result = predict_price(input_features)
   print("Predicted price:", result)
   ```

## Results

The model provides accurate price predictions with a mean absolute error (MAE) of less than 10% of the average price. The visualizations help understand the most important factors influencing bulldozer prices.

## Future Enhancements

- Adding more features for better prediction accuracy.
- Deploying the model using a web application for real-time predictions.
- Integrating additional data sources for improved insights.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue if you have suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, contact [Adeeba Farooq](mailto:adeebafarooq39@gmail.com).
