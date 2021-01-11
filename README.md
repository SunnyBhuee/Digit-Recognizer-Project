# Digit-Recognizer-Project
This is my submission for the Digit Recognizer Project on **Kaggle** using **MNIST** dataset.

**MNIST** is the classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. 

**Problem:** Our goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. 

**Data:** The data files ***train.csv*** and ***test.csv*** contain gray-scale images of hand-drawn digits, from zero through nine. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

**Approach:** We use the train dataset to test two approaches for this dataset i.e. ***K-Nearest Neighbors Classifier*** and ***Decision Tree Classifier***. Then the better of the two approaches, which turns out to be **KNN** with **k=3** is used to classify the images in the test dataset, and results are found to be ***97%*** accurate.

---
