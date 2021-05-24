# FACE-DETECTION

The objective of the program given is to detect object of interest(face) in real time and to keep tracking of the same object.This is a simple example of how to detect face in Python. You can try to use training samples of any other object of your choice to be detected by training the classifier on required objects.

## Algorithms used:

* This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.

 **LBPH uses 4 parameters:**
* Radius: the radius is used to build the circular local binary pattern and represents the radius around the
central pixel.
 * Neighbors : the number of sample points to build the circular local binary pattern.
* Grid X : the number of cells in the horizontal direction.
* Grid Y : the number of cells in the vertical direction.

* The model built is trained with the faces with tag given to them, and later on, the machine is given a test data and machine decides the correct label for it.
