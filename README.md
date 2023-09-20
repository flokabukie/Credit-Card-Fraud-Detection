# Credit-Card-Fraud-Detection
 This project is to build an advanced fraud detection system using neural networks to identify transactions that appear unusual and potentially fraudulent. By applying object-oriented programming (OOPs) concepts, we aim to develop a scalable and modular solution that can handle large volumes of data and provide valuable insights to Company ABC.

### *Overview*
The Credit Card Anomaly Detection project focuses on identifying suspicious transactions within credit card data. Leveraging advanced machine learning algorithms, including Isolation Forest, DBSCAN, and Local Outlier Factor, this system provides an efficient solution for fraud detection.

### *Key Features*
**Multiple Algorithms**

Utilizes Isolation Forest, DBSCAN, and Local Outlier Factor for anomaly detection, allowing for comprehensive coverage.

**Data Preprocessing** 

Includes data scaling and standardization for improved model performance.

**Interactive Interface**

 A user-friendly interface enables easy input of transaction details for real-time anomaly detection.

**Visual Insights** 

Provides visualizations of anomaly scores and location plots for better understanding and decision-making.

### *Models*
**Isolation Forest:**
 A machine learning algorithm for detecting anomalies based on the fact that anomalies are typically far from the majority of data points.

**DBSCAN:**
 A density-based clustering algorithm that identifies regions with a high density of data points as clusters.

**Local Outlier Factor (LOF):** A method for detecting outliers in a dataset by measuring the local deviation of a given data point with respect to its neighbors.

### *Results*
Precision, recall, and AUC-PR scores for each model.

Visualizations demonstrating the performance and effectiveness of the algorithms.
Deployment
This project includes a Streamlit web application that has been deployed on Hugging Face. You can interact with the deployed app here.

Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License.








![Alt text](rtxt.png)

![Alt text](files.png)

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/username/credit-card-anomaly-detection.git
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Data Preparation:

Place transaction data in the data/ directory. Ensure it contains the required columns.
Modify data loading process in utils.py if needed.
Training Models:

Use Jupyter notebooks in the notebooks/ directory for model training and evaluation.
Using the Models:

Load trained models using joblib:
python
Copy code
import joblib

# Load the Isolation Forest model
isolation_forest = joblib.load("models/IsolationForest.joblib")

# Load the StandardScaler
scaler = joblib.load("models/StandardScaler.joblib")
Anomaly Detection:

Utilize the anomaly_detection.py module in the src/ directory for detecting anomalies in new data.
Visualization:

Modify plotting functions in utils.py for custom visualizations.
Models
Isolation Forest: A machine learning algorithm for detecting anomalies based on the fact that anomalies are typically far from the majority of data points.
DBSCAN: A density-based clustering algorithm that identifies regions with a high density of data points as clusters.
Local Outlier Factor (LOF): A method for detecting outliers in a dataset by measuring the local deviation of a given data point with respect to its neighbors.
Results
Precision, recall, and AUC-PR scores for each model.
Visualizations demonstrating the performance and effectiveness of the algorithms.
Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.