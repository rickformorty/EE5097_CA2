# NUS_EE5907_CA2

## How to use my code?

To run my code, Python and Jupyter nootbook is needed. And my Python version is 3.8.2.

Using 'pip install -r .\requirements.txt'  in any one of your virtual environment to install packages used in my CA2.

## About the imported scikit-learn package

It is only for train_test_split function in CNN.ipynb. I did not use it for PCA or LDA.

## Files Introduction

Files in '.\svm\' is used to store datasets that conform to the LibSVM format, and SVM Models are
stored in this folder as well.

Files in '.\*.npy'  are storing the np.array variable to make it easier for me to read the variable directly
while developing, instead of using cv2.read over and over again

Files in '.\*.h5' are the same usage with *.npy, but in a pandas storage formal.
