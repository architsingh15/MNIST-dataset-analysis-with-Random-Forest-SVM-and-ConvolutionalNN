##MNIST-dataset-analysis-with-Random-Forest-and-Support-Vector-Machine
## http://yann.lecun.com/exdb/mnist/ --> get the data set here. 
Four files are available on this site:

train-images-idx3-ubyte.gz:  training set images (9912422 bytes) 
train-labels-idx1-ubyte.gz:  training set labels (28881 bytes) 
t10k-images-idx3-ubyte.gz:   test set images (1648877 bytes) 
t10k-labels-idx1-ubyte.gz:   test set labels (4542 bytes)

Addressing the MNIST Dataset problem using Random Forest Classifier 

1) using sklearn we build a classifier as random forest with 100 trees in the forest and 10 job parallely running capacity

2) undergone testing training split for data set where the testing hold out is 10% 

3) calculated score by fitting the testing data in the pickled model 


