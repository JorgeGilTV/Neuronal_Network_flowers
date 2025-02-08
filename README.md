# Neuronal_Network_flowers
Python script with newronal network to train and predict the flowers 

prerequisites:

pip install scikit-learn
pip install matplotlib
pip install h5py
pip install mahotas

run organize_flowers17.py
run global.py
run train_test.py

this will organice all pictures grouping by type

global will create folders and insert into correct one

train and test will organize all things, train the model and test with different kind of pictures.

the objetive for this python script is to verify the accuracy for below models:

# Machine Learning Models

'LR', LogisticRegression(random_state=seed)
'LDA', LinearDiscriminantAnalysis()
'KNN', KNeighborsClassifier()
'CART', DecisionTreeClassifier(random_state=seed)
'RF', RandomForestClassifier(n_estimators=num_trees, random_state=seed)
'NB', GaussianNB()
'SVM', SVC()