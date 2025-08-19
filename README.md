# Iris Classification using Gaussian Naive Bayes

This project demonstrates **Gaussian Naive Bayes classification** on the classic **Iris dataset** using `scikit-learn`.  
The Iris dataset contains three classes of flowers (*Setosa, Versicolor, Virginica*) with numerical features:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---

## 📊 Project Workflow
1. Load the Iris dataset from `sklearn.datasets`
2. Split the dataset into training and testing sets
3. Train a `GaussianNB` model
4. Make predictions on the test set
5. Evaluate model performance using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

---

## 🚀 Results
- **Accuracy:** 100%  
- **Confusion Matrix:**

[[10 0 0]
[ 0 9 0]
[ 0 0 11]]

- **Classification Report:**
          precision    recall  f1-score   support
       0       1.00      1.00      1.00        10
       1       1.00      1.00      1.00         9
       2       1.00      1.00      1.00        11

accuracy                           1.00        30


macro avg 1.00 1.00 1.00 30
weighted avg 1.00 1.00 1.00 30


---

## ⚙️ Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy

---

## 📂 How to Run
```bash
# Clone the repository
git clone https://github.com/ishanegi5/iris_gaussian_nb_classification.git

# Navigate to the folder
cd iris_gaussian_nb_classification

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script


📜 License

This project is open-source and available under the MIT License.
