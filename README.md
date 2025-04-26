📱 Play Store Data Analysis & Machine Learning Project
This project analyzes and models data from the Google Play Store using Python and machine learning techniques. It was built as part of the Data Warehousing and Data Mining (DWDM) course.


📌 Project Description
The goal of this project is to clean, process, visualize, and model the Play Store dataset. We focus on understanding app characteristics like rating, price, installs, and more, and apply a classification model to predict outcomes.

🧰 Technologies & Libraries Used
Python 3

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn (sklearn)

🗂️ Dataset
Source: Google Play Store Apps Dataset (publicly available)

Columns: App Name, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Android Version, etc.

🚀 Project Workflow
1. Data Loading
Import the CSV file using pandas.

2. Data Cleaning
Convert improper data types (e.g., Installs, Price, Last Updated).

Handle missing values:

Numeric fields: filled with median.

Categorical fields: filled with mode.

Remove duplicates.

3. Data Visualization
Histograms and boxplots to detect outliers.

Distribution analysis for key columns like Rating and Price.

4. Outlier Handling
Remove ratings > 5.

Fix price anomalies.

5. Feature Engineering
Label Encoding for categorical features.

6. Model Building
Random Forest Classifier used for prediction.

Dataset split into training and testing sets (80-20 split).

7. Model Evaluation
Accuracy, Precision, Recall, F1 Score

Classification report generated.

📊 Results
Achieved good performance with Random Forest Classifier.

Identified key features impacting app ratings and installs.

Cleaned dataset ready for further advanced analysis.


Clone the repository:

bash
Copy
Edit
git clone https://github.com/shivamkumar818/Play-Store-Data-Analysis-Machine-Learning-Project-.git
Install the required libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Open the .ipynb file using Jupyter Notebook or Google Colab.

Run the cells one by one.

📬 Contact
For any questions or collaborations, feel free to reach out!

GitHub: shivamkumar818

(Add LinkedIn if you want)

🌟 Acknowledgments
Dataset inspired from Google Play Store app listings.

Special thanks to my DWDM course instructors and peers for guidance!
