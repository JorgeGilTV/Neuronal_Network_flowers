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

Expected results ( not exact ):

[STATUS] features shape: (1360, 532)

[STATUS] labels shape: (1360,)

[STATUS] training started...

[STATUS] splitted train and test data...

Train data  : (1224, 532)

Test data   : (136, 532)

Train labels: (1224,)

Test labels : (136,)

LR: 0.513155 (0.047052)

LDA: 0.448534 (0.031931)

KNN: 0.357044 (0.025681)

CART: 0.483713 (0.025872)

RF: 0.646208 (0.022678)

NB: 0.358670 (0.026739)

SVM: 0.502526 (0.044709)