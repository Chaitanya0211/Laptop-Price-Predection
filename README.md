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
├── requirements.txt                # Python packages requirements
└── ScreenShots/                    # Folder containing screenshots
    ├── Output.png        
    ├── Output.png          
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

The dataset used in this project includes the following features:
- **Company**: The manufacturer of the laptop (e.g., Apple, HP, Dell).
- **TypeName**: The type of laptop (e.g., Ultrabook, Gaming, Notebook).
- **Ram**: Amount of RAM in GB.
- **Weight**: Weight of the laptop in kg.
- **Touchscreen**: Whether the laptop has a touchscreen (0: No, 1: Yes).
- **Ips**: Whether the laptop has an IPS display (0: No, 1: Yes).
- **PPI**: Pixels per inch, a measure of screen resolution.
- **Cpu_brand**: The brand of the CPU (e.g., Intel Core i5, Intel Core i7).
- **HDD**: The size of the hard disk drive in GB.
- **SSD**: The size of the solid-state drive in GB.
- **Gpu_brand**: The brand of the GPU (e.g., Intel, AMD).
- **os**: The operating system (e.g., Windows, Mac).

##### Data Processing

- Data cleaning to handle missing values.
- Feature engineering to convert categorical variables into numerical values using techniques such as one-hot encoding.
- Normalization or standardization of numerical features to ensure all features contribute equally to the model training.

##### Model Selection

- Various regression models were considered, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor.

##### Model Training and Evaluation

- The dataset was split into training and testing sets to evaluate the model's performance.
- Performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared were used to assess the accuracy of the predictions.
- The best-performing model was selected based on these metrics.

#### Structure

- **Introduction**: Overview of the project and its objectives.
- **Data Collection and Exploration**: Detailed analysis of the dataset.
- **Data Processing**: Steps taken to clean and preprocess the data.
- **Model Selection and Training**: Exploration of different models and their performance.
- **Model Evaluation**: Detailed evaluation of model performance using various metrics.
- **Conclusion**: Summary of findings and final thoughts.

#### Screenshots

- (ScreenShots/Screenshot 2024-06-30 174932.png)
- (ScreenShots/2.png)

#### Conclusion

The project successfully built a machine learning model to predict laptop prices with reasonable accuracy. The Random Forest Regressor was found to be the best-performing model, providing the lowest Mean Absolute Error and highest R-squared value. Future work could include exploring additional features, using more advanced models, and incorporating real-time price updates to improve prediction accuracy further.
