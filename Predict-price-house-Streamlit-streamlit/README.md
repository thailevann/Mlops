# Real Estate Price Prediction

This project leverages a dataset containing information on properties, including:
- **Bedrooms**: Number of bedrooms
- **Bathrooms**: Number of bathrooms
- **Size**: Size of the property
- **Latitude**: Latitude coordinate
- **Longitude**: Longitude coordinate

The data is used to train a **Random Forest** regression model, and the details of the model training process are stored in the `train_model` folder.

## Getting Started

1. Clone this repository to your local machine.
2. Install all required packages by running:
   ```bash
   pip install -r requirements.txt
3. Train the model in the train_model folder. After running the following cell, make sure to save the model in the model folder.:
  ```bash
  import pickle
  with open('model.pkl', 'wb') as file:
      pickle.dump(rf_regressor, file)
4. Building the Web Application using Streamlit:
Run the following command in your terminal
  ```bash
  streamlit run streamlit_app.py

## Video demo
