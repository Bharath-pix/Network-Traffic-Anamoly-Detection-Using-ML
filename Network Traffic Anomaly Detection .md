# **Network Traffic Anomaly Detection**

This project aims to detect anomalies in network traffic using machine learning techniques. The approach is implemented in a Jupyter notebook, which processes and analyzes the dataset to identify irregular patterns that may indicate cyber threats or unusual behavior.

## **Dataset**

Source: [Kaggle \- Network Traffic Anomaly Detection Dataset](https://www.kaggle.com/datasets/ziya07/network-traffic-anomaly-detection-dataset)

Files in Dataset:

* dataset.csv: Contains network traffic logs with the following features:

  * Flow ID

  * Source IP, Destination IP

  * Source Port, Destination Port

  * Protocol, Timestamp

  * Flow Duration, Packet Count, Byte Count

  * Label: Indicates whether the flow is Anomalous or Benign

## **Project Structure**

bash  
CopyEdit  
`anomaly-detection/`  
`│`  
`├── notebooke3b18137c6.ipynb      # Main Jupyter notebook (uploaded)`  
`├── README.md                     # Project documentation`  
`├── data/                         # Folder for storing dataset files`  
`│   └── dataset.csv`

## **Features Implemented**

* Data preprocessing (cleaning, encoding, handling missing values)

* Exploratory Data Analysis (EDA)

* Feature selection

* Train/Test splitting

* Model training using:

  * Logistic Regression

  * Random Forest

  * XGBoost

* Performance metrics:

  * Accuracy

  * Precision/Recall/F1 Score

  * Confusion Matrix

## **Requirements**

Install required Python libraries with:

bash  
CopyEdit  
`pip install -r requirements.txt`

Example libraries:

* pandas

* numpy

* scikit-learn

* matplotlib

* seaborn

* xgboost

## **How to Run**

1. Place dataset.csv in a folder named data

Open the notebook:

 bash  
CopyEdit  
`jupyter notebook notebooke3b18137c6.ipynb`

2.   
3. Run all cells to process the data and train models

## **Results**

* Accuracy achieved: \~X% (replace with your results)

* Best performing model: Random Forest / XGBoost / etc.

* Top features influencing anomaly detection identified

## **References**

* [Kaggle Dataset](https://www.kaggle.com/datasets/ziya07/network-traffic-anomaly-detection-dataset)

* Scikit-learn documentation

* Network security literature on anomaly detection

## **License**

This project is licensed under the MIT License

## **Author**

Bharath Narasimha Sai Boddu

Meesala Eesha

Lanka Mokshagna Reddy 

## **Video Explanation** 

[intel unnati.mp4](https://drive.google.com/file/d/1j-DnT9iK9v5aZ8dPJQQ_ymCLyHocnDkH/view?usp=sharing)