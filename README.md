# Traffic Sign Classification
 This project builds a convolution neural network (CNN) for classifying traffic signs. The German Traffic Sign 
Recognition Benchmark (GTSRB    ) dataset has been used for the project.

                   <--- This is a work in progress... --->

Following are the key steps that has been followed in this project
  
1. Data Loading
2. Data Analysis
3. Data Preprocessing
4. Build the CNN Model
5. Training and Performance Monitoring of the Model
6. Testing the Model
  
## 1. Data Loading
A pickled version of a subset the GTSRB dataset has been used in the Trffic_Sign_Classifier.ipynb file. The pickled data is a dictionary with 4 key/value pairs:
 
* 'features' is a 4D array containing raw pixel data of the traffic sign images, (num examples, width, height, channels).
* 'labels' is a 1D array containing the label/class id of the traffic sign. The file signnames.csv contains id -> name mappings for each i    d.
* 'sizes' is a list containing tuples, (width, height) representing the original width and height the image.
* 'coords' is a list containing tuples, (x1, y1, x2, y2) representing coordinates of a bounding box around the sign in the image.
  For this project only the 'feature' and 'labels' data have been used.
 
## 2. Data Analysis
* checking the trainng and testing images and labels
* visualization of images
  
## 3. Data Preprocessing
* resizing of images
* flattening the images to make them suitable for the model training
* normalization of images
* one-hot-encoding of labels
  
## 4. Build the CNN Model
A simple CNN wih
* three  fully connected hidden layers
* a dropout layer
* an ouput layer with classes equal to the number of differnt traffic signs

## 5. Training and Performance Monitoring of the Model
* optimze the model using Stochastic Gradient Descent (SGD) optimizer
* visualize the training and validation loss & accuracy

## 6. Testing the model
* test the model using test data
                                                                                                                    

