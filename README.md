# Neural-network

## Project

The main goal of this project is to recognize the sport displayed by an image.
For this task we downloaded data from 22 differents sports and reduce them to only 15 sports.
which are : 
badminton,
baseball,
basketball,
boxing,
cricket,
football,
gymnastics,
hockey,
swimming,
table_tennis,
tennis,
volleyball,
weight_lifting,
wrestling,
wwe

To succeed in this task we used transfer learning method from model trained on imagenet.
The project is divided into three main parts. Each part is showing the influence of a certain parameter on the results.
Notice that in this project, du to a lack of computer power, hyperparameters are not optimized.
The first part treat about diffrent pre-trained moodels. The second part tackle the quality of the input image (size and blur).
The last part is about the accuracy of the model given a certain amount of class.

## Files

The data directory in this project regroup all the images we used to trained the network. The csv in this directory regroup the labels and path of each image.
Each jupyter notebook has a single task :

dataset_load.ipynb      : Used to load the datasets and to create the csv file
image_size.ipynb        : Train alexnet network for different quality of image input
import_train_NN.ipynb   : Train 4 differents networks on the same dataset
nb_classes.ipynb        : Train resnet network on three different number of classes to predict (done with a mac computer)
compare_NN.ipynb        : Compare all the trained convolutionnal neural networks

The trained model are stored in a separate directory because the files were too big to be stored on github : https://drive.google.com/drive/u/0/folders/1aIh3Pye3oQbDvRpnJbqEE1pRsAy6nDhX
The accuracies of the trained  model at each epoch are stored in the txt files.