# MNIST Classification
#### Dataset : mnist_784
- **Source** : sklearn.datasets -> fetch_openml('mnist_784', version = 1)
- **Structure**
    - DESCR key - Describes the dataset
    - data key - Dataset features
    - target key - Dataset labels
- Dataset has 70000 images and 784 (28 x 28) features. Each instance (row) represents an image. each feature represents a pixel's intensity from 0 (white) to 255 (black).

#### Objective
- Build a classifier to predict label for the given features (28 x 28).

#### Disclaimer
<ul>This project is to use technics shown in the book - Hands On Ml 2. We will try to outperform the outcome of chapter 3 - Classification Machine Learning project. We will also be using code from Hands On Ml 2 github repository.</ul>
