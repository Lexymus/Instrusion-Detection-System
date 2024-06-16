# Instrusion-Detection-System
Requirements :
numpy, 
pandas,
matplotlib, and seaborn. 
Machine learning and feature selection are facilitated by 
scikit-learn (provides various classifiers and preprocessing tools like StandardScaler, LabelEncoder, and RFE (Recursive Feature Elimination)) 
tensorflow

!pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm tabulate tensorflow

Code Functionality:
The provided code performs a comprehensive analysis and comparison of various machine learning models for intrusion detection. Initially, it preprocesses the dataset by encoding categorical variables and scaling the features. Recursive Feature Elimination (RFE) is used to select the top features contributing to the prediction task. The dataset is split into training and test sets, and several machine learning models (SVM, Random Forest, Gradient Boosting, and Logistic Regression) are trained and evaluated on these sets. Each model's performance is measured using accuracy and F1 score. A deep learning model is also incorporated, built using Keras within TensorFlow, which includes layers with dropout to prevent overfitting, and an EarlyStopping callback to halt training when the validation loss stops improving. The performance of all models is visualized in a bar graph comparing their accuracy and F1 scores, providing a clear, comparative insight into their effectiveness in intrusion detection.
Dataset: dataset are uploaded in the repo
