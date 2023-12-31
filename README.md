# Animal_Detection_System
In this project we implemented and studied an Animal Detection System, aiming at both high detection accuracy and computational efficiency. 

Specifically, we studied a two-stage detection method. The reason we employ two machine learning algorithms is the reduction of the false-positive rate and the execution time required for the multi-scale detection procedure of an input image. In the first stage, we use the Histogram of Oriented Gradient (HOG) descriptor and a Support Vector Machine (SVM) classifier that provides the next stage with a set of regions of interest (ROI) containing target animals and other false positive targets. Subsequently, the second stage, rejects the false positive by using a Convolutional Neural Network (CNN) classifier. To train and evaluate the animal detector, we use CIFAR-10 dataset. The purpose of this method was to detect animals from images and videos captured in natural scenes. For our experiments we used deers as the animal of choice.

For the classification algorithms we made use of OpenCV and Caffe frameworks
