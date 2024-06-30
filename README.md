#### Project Overview
**Title**: Laptop Price Predictor

**Objective**: 
To build a machine learning model that predicts the price of laptops based on various features such as company, type, RAM, weight, touchscreen, IPS, PPI, CPU brand, HDD, SSD, GPU brand, and operating system.

#### Project Structure

```
laptop-price-predictor/
│
├── Data/
│   └── laptops.csv                 # Dataset used for training the model
│
├── .gitignore                      # Git ignore file
├── LICENSE                         # License file
├── Laptop_Price_Predictor.ipynb    # Jupyter Notebook with the project code
├── README.md                       # Project README file
├── app.py                          # Main Flask application
├── laptop_data.pkl                 # Preprocessed data for the model
├── pipe.pkl                        # Serialized machine learning pipeline
└── requirements.txt                # Python packages requirements
```

#### Installation
1. Clone the repository:
   ```
   git clone https://github.com/Chaitanya0211/Laptop-Price-Predection.git
   cd laptop-price-predictor
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

#### Usage
1. Run the Jupyter Notebook to explore the data, train the model, and evaluate its performance:
   ```
   jupyter notebook Laptop_Price_Predictor.ipynb
   ```
2. Run the Flask application:
   ```
   python app.py
   ```

#### Project Details

##### Data Collection
- The dataset includes various features related to laptop specifications.

##### Data Processing
- Data cleaning and feature engineering steps are performed to prepare the data for modeling.

##### Model Selection
- Various regression models are evaluated, and the best-performing model is selected.

##### Model Evaluation
- Performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared are used to assess the model's accuracy.

#### Conclusion
The project successfully built a machine learning model to predict laptop prices with reasonable accuracy. Future improvements could include adding more features and using advanced models to enhance prediction accuracy.
