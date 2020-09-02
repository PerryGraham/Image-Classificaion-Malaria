# Image-Classificaion-Malaria
Binary image classification of blood smear to determine parasite presence using TensorFlow 

[Click here to view the notebook on Kaggle](https://www.kaggle.com/perry613/malaria-blood-smear-classifier-tensorflow)

The purpose if this notebook is to try using a CNN model with TensorFlow to classify thin blood smears. More specifically, detecting the presence of parasites. With the use of smartphones with a small microscopic attachment, large scale blood smear tests can be done in developing countries. However, there is a limitation with the amount of expects that are able to determine the results of the tests. Computer vision can help solve this problem. Here is some code with an  explanation to implement a convolutional neural network to handle this classification. 

Data from [Malaria Cell Images Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria) uploaded by: [Arunava](https://www.kaggle.com/iarunava)

The final accuracy of this model was around 95%. After investigating the incorrect predictions, there seems to be some labels that are incorrect within the dataset.

# Parasitized 

![](https://i.imgur.com/kYa4l2G.png)

# Uninfected 

![](https://i.imgur.com/Wd5EDKd.png)

# Prediction Confusion Matrix 

![](https://i.imgur.com/EpMG7tM.png)
