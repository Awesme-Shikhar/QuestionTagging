# Stackoverflow Questions Multitagging

## About the project
   
We have used jupyter notebook for executing our project. Kindly run the project by executing the jupyter python files in the following sequence.Also paste these files in a folder containing questions.csv,answers.csv,tags.csv. These 3 files can be downloaded from the following link https://www.kaggle.com/stackoverflow/stacksample:
   
1. tags.ipynb        - Function of this file is to select 50 tags and save question id list.
2. prepareY.ipynb    - This file converts the top 50 tags into binary label matrix for each question pertaining to these 50 tags.
3. questions.ipynb   - This file will filter the selected questions associated with these 50 tags followed by preprocessing of   text and save list of questions .
4. splitDataset.ipynb - Takes the binary label matrix and saved question list and split into training data and test 
                           data set.
5. Train one of the selected models after completing execution of files from points A to D.
   - Model1- Corresponds to Random Forrest Classifier
   - Model2- Corresponds to SGD Classifier(You can switch to 4 different versions of SGD by making changes in cell 4 and cell 6(for getting different trained models in the form of .pkl file)
   - Model3- Corresponds to MLP Classifier.

## Running the code

Use joblib from sklearn.externals for using the train models generated in the .pkl files. Alternatively you can use our trained models present in the form of .pkl files in the google drive link we have provided below and use the test data that we have provided in the form of Xtest.pkl and Ytest.pkl.GOOGLE DRIVE [LINK](https://drive.google.com/drive/folders/1zmAywh9dCSDgUbSG7JA72ppGyvGDU7iV?usp=sharing) OF TRAINED MODELS.
