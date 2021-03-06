# CNN-based-Real-Time-Handwritten-Digit-Rcognition
The objective of this project is to recognize handwritten digits based on real time image acquisition from a camera. 
Currently, several algorithms are suitable for this classification task, such as Bag of Words approach, Decision Trees or 
Artificial Neural Networks (ANN). However, the most powerful image recognition tools are based on Convolutional Neural 
Network (CNN), which is going to be the approach chosen for this project. 

Matlab scripts were used, along with Image Recognition Toolbox. For training and testing MNIST dataset was used. 
The final net achieved a 98.54% train accuracy and 98.40% test accuracy. For real time segmentation, blob analysis 
was carried out, and for digit preprocessing, resize and Gauss filter were used to adequate each detected digit to 
CNN input. The final model was tested in a 1280x720 Webcam with sample time of 1 sec.

FUNCTIONS:

-- loadMNISTLabels: load MNIST labels, one label per image

-- loadMNISTImages: load MNIST 28x28 images

-- imgsquarebin:    reshape binary image into squared

-- imgnormalize:    normalize image values within 0 to 255

-- imgblobdetect:   Extract blob objects from image I as 4-D matrix of images and assigns a bounding box. Output images are                       ready to be tested on CNN. Only uint8 input images.


** MAIN FILES:

-- main_cnn_custom_train

-- main_webcam_video



