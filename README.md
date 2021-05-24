# PCA-ImageRec
A demonstration of using Principal Component Analysis to identify gender in human images

Used as part of TCSS 544 Applied Linear Algebra project and paper demonstrating the use of PCA and SVD for image classification in the spring of 2016. 

Matlab code created to do gender classification of images using Principal Component Analysis. The images were a subset of the Essex set of publicly available face images (centered, controlled images). PCA was performed two different classes of images, male and female, creating two coordinate spaces. Classification was performed by projecting example images into each coordinate space of eigen-vectors and then re-projecting them into the original basis vectors. The class with the minimal error of reprojection was selected for each example. Various numbers of eigenvectors were tested, checking for the minimal number of eigen-vectors that were needed to achieve high accuracy. For this data set, 20 eigen-vectors or more yielded 100% accuracy of gender classification of test images from the same set (held out from training).

This is purely intended as a code sample for prospective employers or partners at this time.

[Armer_Kaplan_project_TCSS-544_V7-final.pdf](https://github.com/DaveK2301/PCA-ImageRec/files/6533500/Armer_Kaplan_project_TCSS-544_V7-final.pdf)
