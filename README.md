# Handwritten Digit Recogniser

## Why is it important?
Digit Recognition is a noteworthy and important issue. As the manually written digits are not of a similar size, thickness, position and direction, in this manner, various difficulties must be considered to determine the issue of handwritten digit recognition. The uniqueness and assortment in the composition styles of various individuals additionally influence the example and presence of the digits.

## Modules and Methods
This project has been divided into 4 Modules. These include Data Pre-Processing, Segmentation, Feature Extraction and Classification & Regression. In Pre-Processing, we perform various tasks on the input image. Noise filtering, smoothing and standardization are to be done in this stage. Pre-processed digit images are segmented into a sub-image of individual digits, which are assigned a number to each digit. Each individual digit is resized into pixels. In Feature Extraction, the pre-processed images are represented in the form of a matrix which contains pixels of the images that are of very large size. In the classification and recognition step the extracted feature vectors are taken as an individual input to each of the following classifiers. We use classifiers like K-Nearest Neighbor, Random Forest Classifier and Support Vector.

## Discussion
There is a debate about which out of the most widely used ML algorithms i.e. KNN, SVM, RFC, and CNN is a better technique for handwritten digit recognition.
Anuj Dutt in his paper demonstrated that utilizing Deep Learning systems, he had the capacity to get an extremely high measure of accuracy.
General issue confronted would be of digit order issue and the closeness between the digits like 1 and 7, 5 and 6, 3 and 8, 9 and 8 and so forth.
