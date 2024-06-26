## Machine Learning Projects

![MasterHead](https://github.com/ISmokeData/DiamondPricePrediction/blob/7a6d6c13b77d920c984340e34fbcb0f14c11aba0/images/gem.png)


This repository contains a Diamond Price Prediction model built using machine learning techniques. The model utilizes a dataset sourced from Kaggle, which contains information about gemstones. The project encompasses various stages including data preprocessing, exploratory data analysis (EDA), feature engineering, feature selection, and model training. Finally, the model is deployed using Flask, providing a platform to interactively predict diamond prices through a web interface.:

### Files Included:
1. **Dataset (CSV)**: Contains the gemstone dataset collected from Kaggle.
   - File Name: `gemstone.csv`

2. **Model Building Notebook (Jupyter Notebook)**: This notebook outlines the process of feature engineering, exploratory data analysis (EDA), feature selection, and model building using various regression techniques.
   - File Name: `EDA.ipynb`

3. **Flask App Directory**:
   - **App.py**: Contains the Flask web application code to deploy the model.
   - **Templates Directory**: Contains HTML templates for rendering the web interface.
   - **Static Directory**: Contains static files (e.g., CSS, JavaScript) for the web interface.

4. **Trained Models**: Contains the serialized trained models for each regression technique.
   - File Names:
     - `model_training.ipynb`
     - `model.pkl`


5. **Requirements.txt**: Lists all the dependencies required to run the Flask application.

### Model Building Process:
The notebook `diamond_price_prediction.ipynb` provides a detailed walkthrough of the model building process, including:
- Feature engineering to extract meaningful features from the dataset.
- Exploratory data analysis (EDA) to gain insights into the data.
- Feature selection techniques to identify the most relevant features for prediction.
- Implementation of machine learning models including Linear Regression, Ridge Regression, Lasso Regression, and Decision Tree Regressor.
- Evaluation of model performance and selection of the best performing model.

### Flask Web Application:
The Flask web application (`app.py`) serves as the interface for users to interact with the trained model. Users can input diamond features through a web form, and the application predicts the price using the selected model. The web interface is rendered using HTML templates located in the `templates` directory.


![screenshot](https://github.com/ISmokeData/DiamondPricePrediction/blob/68f3b80574c703b7d24d49e58baf93bee9f262b8/images/Screenshot%20(123).png)



### Deployment:
The project utilizes Flask's `render_template` function to render the web interface, enabling easy deployment. Simply run `app.py` to start the Flask server and access the application through a web browser.

### How to Use:
1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Explore the `diamond_price_prediction.ipynb` notebook to understand the model building process.
4. Run `app.py` to start the Flask server.
5. Access the web application through your browser and input diamond features to predict prices.

### Note:
- The gemstone dataset used in this project is sourced from Kaggle, respecting Kaggle's terms of service and guidelines.
- For any inquiries or issues, feel free to contact the repository owner.

 **Kaggle :** https://www.kaggle.com/datasets/dhanrajcodes/gemstone-price/data
  
Thank you for using this repository to explore diamond price prediction with machine learning techniques!
