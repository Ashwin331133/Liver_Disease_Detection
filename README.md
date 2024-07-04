# Liver Disease Detection

## Objective

The main objective of this project is to use classification algorithms to detect liver patients from healthy individuals. Three classification algorithms, namely Logistic Regression, K Nearest Neighbor (KNN), and Artificial Neural Networks (ANN), were evaluated based on their performance using liver patient data. The algorithm with the highest accuracy was implemented into a user-friendly GUI using Flask in Python, designed to assist doctors and medical practitioners in screening for liver disease.

## Dataset

The dataset used is The Indian Liver Patient Dataset (ILPD) from the UCI Machine Learning Repository. It consists of 416 liver patient records and 167 non-liver patient records collected from North East of Andhra Pradesh, India. The dataset includes 441 male patient records and 142 female patient records. The "Dataset" column serves as the class label, dividing patients into liver disease and no disease groups.

## Libraries Used

- Numpy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn
- Flask (for GUI implementation)
- HTML
- CSS

## Conclusion

In this project, we have proposed methods for diagnosing liver disease in patients using machine learning techniques. The different machine learning techniques that were used include Logistic Regression, KNN, Support vector Machine, Gaussian Naive bayes, Random forest and XGB classifier. The system was implemented using all the models and their performance was evaluated. Performance evaluation was based on model accuracy. Random forest was the model that resulted in the highest accuracy. A GUI is developed using Flask and implemented using Random forest. The system will predict whether the patient has liver disease or not based on the trained model. The GUI will be a useful tool for medical staff in the early detection of liver disease in patients
