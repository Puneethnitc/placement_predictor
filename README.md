Placement Prediction using Machine Learning

Overview
This project predicts whether a student will be placed or not based on academic performance, skills, and training-related factors using a Machine Learning model.
The goal is to analyze the placement dataset, understand factors influencing placements, and build a predictive model achieving more than 60% accuracy.

Dataset
Placement Dataset containing student academic and skill-related information
Target variable: PlacementStatus (Placed / NotPlaced)
Total records: 10,000 students

Exploratory Data Analysis (EDA)
The following analyses were performed:

Distribution of placed vs not placed students
Relationship between CGPA and placement
Impact of internships, projects, aptitude score, and soft skills
Effect of placement training and extracurricular activities
Correlation analysis using heatmaps

Key observations:
Aptitude score, placement training, and extracurricular activities strongly influence placement
CGPA, projects, and internships have moderate influence

Data Preprocessing
Converted categorical variables to numerical format
Performed train-test split with stratification
Applied feature normalization using StandardScaler
Ensured no data leakage by fitting the scaler only on training data

Model Building
Algorithm used: Logistic Regression
Reason: Suitable for binary classification and easy to interpret
Model trained on scaled training data

Model Evaluation
Evaluation metric: Accuracy
Final Accuracy: approximately 80.5 percent
Confusion matrix used to analyze prediction performance

The model exceeds the required accuracy threshold of 60 percent.

Conclusion
The Logistic Regression model successfully predicts student placement outcomes.
The results show that placement depends on a combination of academic performance, skills, and training rather than a single factor.

Tools and Libraries
Python
Pandas and NumPy
Matplotlib and Seaborn
Scikit-learn

How to Run
Clone the repository
Open the Jupyter Notebook
Run all cells sequentially

Author
Puneeth Mandugundu
