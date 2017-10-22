# CNN-based-Real-Time-Handwritten-Digit-Rcognition
The objective of this project is to recognize handwritten digits based on real time image acquisition from a camera. 
Currently, several algorithms are suitable for this classification task, such as Bag of Words approach, Decision Trees or 
Artificial Neural Networks (ANN). However, the most powerful image recognition tools are based on Convolutional Neural 
Network (CNN), which is going to be the approach chosen for this project. 

For training and testing MNIST dataset was used. The final net achieved a 98.54% train accuracy and 98.40% test accuracy. 
For real time segmentation, blob analysis was carried out, and for digit preprocessing, resize and Gauss filter were used 
to adequate each detected digit to CNN input. The final model was tested in a 1280x720 Webcam with sample time of 1 sec.
