Crop Recommendation System
Project Overview
This project aims to build a Crop Recommendation System that suggests the most suitable crop based on specific environmental parameters like Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall. The system uses various machine learning models to predict the best crop for given conditions.

Dataset
The dataset used for this project is the Crop_recommendation.csv, which contains the following features:

N: Nitrogen content in the soil
P: Phosphorus content in the soil
K: Potassium content in the soil
temperature: Temperature in degrees Celsius
humidity: Relative humidity in percentage
ph: pH value of the soil
rainfall: Rainfall in mm
label: Crop type
The dataset contains 2,200 entries and 22 different crops.

Prerequisites
Make sure you have the following installed:

Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
You can install the required libraries using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/crop-recommendation-system.git
cd crop-recommendation-system
Load the dataset:
Ensure that the Crop_recommendation.csv file is in the same directory as the script.

Run the script:

bash
Copy code
python crop_recommendation.py
Output:
The script will output the accuracy of different machine learning models used in the project and provide a classification report for each model.

Models Used
The following machine learning models have been implemented and evaluated:

Decision Tree: A decision tree classifier that splits the data into branches to make decisions.
Naive Bayes (GaussianNB): A probabilistic classifier based on applying Bayes' theorem.
Logistic Regression: A regression model to predict the probability of a categorical outcome.
K-Nearest Neighbors (KNN): A non-parametric method that classifies samples based on the majority vote of their neighbors.
Model Performance
Each model's accuracy has been evaluated using a test set and cross-validation:

Decision Tree: ~90% accuracy
Naive Bayes: ~99% accuracy
Logistic Regression: ~95% accuracy
KNN: ~97.5% accuracy
These results indicate that the Naive Bayes model performs best on this dataset.

Heatmap of Feature Correlations
A heatmap is generated to show the correlations between the different features in the dataset, helping to understand the relationships among them.


License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
The dataset used in this project was provided by the organization/author.
The project is inspired by the need to support farmers with accurate crop recommendations based on soil and environmental conditions