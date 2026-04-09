 # Leaf Species Detection using Decision Tree


This project demonstrates how to classify leaf species using a Decision Tree Classifier.
We use the famous Iris dataset to train and evaluate the model.

The goal is to predict the species of a leaf based on its features such as:

Sepal length
Sepal width
Petal length
Petal width

 
 
 
          # Algorithm Used
Decision Tree Classifier
Criterion: Entropy (Information Gain)
             # Dataset
Built-in dataset from sklearn.datasets
Total samples: 150
Features: 4
Classes:
Setosa
Versicolor
Virginica
        Technologies Used
Python 
NumPy
Pandas
Matplotlib
Scikit-learn
          Steps Involved
1. Import Libraries
Load required Python libraries
2. Load Dataset
Use load_iris() to import dataset
3. Data Preprocessing
Convert data into DataFrame
Separate features (X) and target (Y)
4. Train-Test Split
75% training data
25% testing data
5. Model Training
Train Decision Tree with different max_depth
Choose best depth based on accuracy
6. Prediction
Predict results using test data
7. Evaluation
Calculate accuracy score
  Model Performance
Achieved Accuracy: ~95% to 100%
Best max_depth: 3
 Visualization
Graph plotted to find best max_depth
Decision tree visualization (optional)
    How to Run
# Clone the repository
git clone https://github.com/your-username/leaf-species-detection.git

# Navigate to project folder
cd leaf-species-detection

# Run the script
python your_script_name.py
 Sample Output
Predicted vs Actual values comparison
Accuracy score displayed
 Future Improvements
Use real leaf image dataset 
Apply Deep Learning (CNN)
Build a web app using Flask/Streamlit
 Conclusion

This project shows how a Decision Tree can effectively classify leaf species with high accuracy using simple machine learning techniques.

📎 Author
fathimath zuhra.c
