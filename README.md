# Celebrity Image Classifier

A dataset consisting 10 celebritries are used for image classification. Classification models such as SVM, Logistic Regression and Random Forest are used.

Following steps are performed for classification:

1. Data Collection: For this project, I am downloading a small dataset from kagel

2. Cleaning Dataset: OpenCV is used to detect face and eyes. All those images where two eyes are not properly visible are discarded.

3. Feature Engineering: Wavelet transform is used to extract important features of the face.

4. Training Model for Classification: SVM, Logistic Regression and Random Forest are used for classification. GridSearchCV is used for hyperparameter tuning.

## Technologies used in this project,
1. Python 3.8
2. Numpy and OpenCV for data cleaning
3. Matplotlib & Seaborn for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for http server
7. HTML/CSS/Javascript for UI

## Folder structure
1. UI : This contains ui website code
2. server: Contains the Python flask server related code
3. model: Contains python notebook for model building
