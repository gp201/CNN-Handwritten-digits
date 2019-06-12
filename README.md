# CNN-Handwritten-digits
This is a CNN used to classify handwritten digits. This method shows a higher accuracy.   
Dataset: MNIST dataset from google
Keras,tensorflow is used.  
Model:  
 1. Convolutional layer with 30 feature maps of size 5×5.  
 2. Pooling layer taking the max over 2*2 patches.  
 3. Convolutional layer with 15 feature maps of size 3×3.  
 4. Pooling layer taking the max over 2*2 patches.  
 5. Dropout layer with a probability of 20%.  
 6. Flatten layer.  
 7. Fully connected layer with 128 neurons and rectifier activation.  
 8. Fully connected layer with 50 neurons and rectifier activation.  
 9. Output layer.  
