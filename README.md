# Dog_Breed_Identification
Self-Project
## Project Topic
How often do you get stuck thinking about the name of a dog’s breed? There are many dog breeds and most of them are similar to each other. We can use the dog breeds dataset and build a model that will classify different dog breeds from an image. This project will be useful for a lot of people.
## Dataset Availibity
https://www.kaggle.com/c/dog-breed-identification
## Project Description
A jupyter file named "Pickle_File_Creation" is used to create pickle files of different feature extraction methods like pretrained DenseNets, ResNets and Vision Image Transformers (ViT's) available in PyTorch along with Histogram of Oriented Gradients (HOG)
In the main file (Dog_Breed_classifer) required pickle files are loaded. Feature selection techniques like Mutual Information were used on individual features extracted from Deep Learning methods and non-Deep learning method (HOG). Feature Reduction technique like Principal Component Analysis (PCA) is also applied on individual features to reduce feature space.
Later, both these feature vectors are concatenated and splitted into training and testing sets. These were then used to train various classifiers like Support Vector Classifier (SVM), Random Forest Classifier (RFC), K-Nearest Neighbours (KNN), Decision Tree Classifier (DTC) and Naive Bayes (GNB).
Various metrics were calculated and plotted for evaluvation model performance. 
