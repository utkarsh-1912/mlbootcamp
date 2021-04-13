# mlbootcamp

### About Dataset:
               1)Training and Testing datasets are MNIST Datasets with 28 X 28 px handwritten number image unit.
               2)Training Dataset =(19999,785) & Testing Dataset =(9999,795) 
## Neural Network
 Learning Rate=0.01
 Accuracy = 87.89 % after 500 itelatration.
 W1,W2 are Weight for layer 1 and layer 2 respectively.
 b1,b2 are Biases.
 Gradient Descent is used to improve accuracy for prediction and is carried out through Backward Propogration function.
 W1 is matrics of dimension 10 X 784.
 W2 is matrics of dimension 10 X 10.
 max_v function is non linear activation function which is actually a rectified linear unit(If x>0 : max_v=x; otherwise max_v=0).
 For second layer ,I apply softmax function.
 
## KNearestNeighbour
Number of Nearest Neighbour under consideration =5
My model Accuracy = 93.63 %
Accuracy from Scikit learn = 95.90%

## Tech Stack Used :
     1)Liberaries--Numpy , Pandas , Matplotlib
     2)Jupyter Notebook
     3) Google Colab

## Programming Language Used : Python

### Note:
         1) KNN WOC  is file with accuracy functions.
         2)Pridicting a value at a time using function 'plotimg'. 
