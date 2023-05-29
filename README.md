# Optical-Recognition-of-Handwritten-Digits
In this problem, K-NN classification will be used to recognize the handwritten digits. Load dataset by sklearn “load_digits” function. 
(https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits)

a) Load the dataset; then, shuffle it. Select 16 random sample from dataset and show them in one 4*4 plot with related label. (Note: each sample is a vector from R64; only for plotting part you should convert it to a 8*8 matric that indicating related gray-scale image)

b) Implement K-NN classification algorithms with two distance metrices (Euclidean and Cosine).

c) Split dataset into train and test sets with ratio of 8:2; using Elbow technique, find optimal K for each distance metric. Report Elbow charts and optimal Ks. Discuss about obtained results.

d) Which distance metric has better performance? Why? Justify your answers.

e) Select a random sample from test set and plot its neighbor digits based on obtained optimal K for both metrics. Discuss about selected neighbors based on different metrics.

f) Report confusion matrices for optimal K and both metrics.

g) Based on obtained confusion matrices, for optimal K and Euclidean distance calculate TP, TN, FP, FN, F1-score. (First, assume that number 8 is true; second, assume that number 3 is true)

h) Repeat previous part for Cosine. (First, assume that number 6 is true; second, assume that number 4 is true)
