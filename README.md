# Face-Verification-App
Face verification using Siamese networks integrated into a Kivy app

Data from collecting negative images: http://vis-www.cs.umass.edu/lfw/#download

As part of this assignment, I learned how to build a deep facial recognition application that validates if a given face matches a set of defined faces.
The following processes were followed to achieve the desired result:
1.	Setup
a.	Installing the required libraries to start with the development
b.	Setting up path folders to store image data
2.	Collect positive images and anchor images
a.	Establishing a connection to a webcam to capture positive images
3.	Data Augmentation
a.	method to generate new training data without changing the class labels by changing brightness, contrast, flipping left to right, quality of image, and saturation of the image.
4.	Load and preprocess images
a.	Creating labeled dataset 
b.	Building data loader pipeline
c.	Creating training partition
d.	Creating testing partition
5.	Model Engineering
a.	Build embedding layer
b.	Build distance layer
c.	Make Siamese network model
6.	Training the Model
a.	Setup loss and optimizer
b.	Establish checkpoints
c.	Build train step function
d.	Build training loop
7.	Evaluate the model
a.	Import metric calculations
b.	Get a batch of test data 
c.	Make predictions
d.	Post processing the results
e.	Creating a metric object
f.	Calculating the recall value
g.	Return recall result
8.	Visualising results
9.	Saving Model
10.	Real Time Testing

