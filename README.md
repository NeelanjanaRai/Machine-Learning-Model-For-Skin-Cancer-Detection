# Machine-Learning-Model-For-Skin-Cancer-Detection
Skin cancer is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopic analysis, a biopsy and histopathological examination. Automated classification of skin lesions using images is a challenging task owing to the fine-grained variability in the appearance of skin lesions.

# Dataset used
This the HAM10000 ("Human Against Machine with 10000 training images"
It consists of 10015 dermatoscopicimages which are released as a training set for academic machine learning purposes and are publiclyavailable through the ISIC archive.

It has 7 different classes of skin cancer which are listed below :
1. Melanocytic nevi
2. Melanoma
3. Benign keratosis-like lesions
4. Basal cell carcinoma
5. Actinic keratoses
6. Vascular lesions
7. Dermatofibroma


# Project lifecycle
Step 1 : Importing Essential Libraries
Step 2: Making Dictionary of images and labels
Step 3: Reading and Processing Data
Step 4: Data Cleaning
Step 5: Exploratory data analysis (EDA)
Step 6: Loading & Resizing of images
Step 7: Train Test Split
Step 8: Normalization
Step 9: Label Encoding
Step 10: Train validation split
Step 11: Model Building (CNN)
Step 12: Setting Optimizer & Annealing
Step 13: Fitting the model
Step 14: Model Evaluation (Testing and validation accuracy, confusion matrix, analysis of misclassified instances)

#

Python Standard Libraries:
os: Provides a way of using operating system-dependent functionality.
  itertools: Implements a number of iterator building blocks inspired by constructs from APL, Haskell, and SML.
External Libraries:
  matplotlib.pyplot: Used for plotting and visualizing data.
  %matplotlib inline: A magic command that allows inline plotting in Jupyter Notebooks.
  numpy: Provides support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
  pandas: A data manipulation and analysis library.
  glob: Used to retrieve files/pathnames matching a specified pattern.
  seaborn: A statistical data visualization library built on top of matplotlib.
  PIL.Image: Part of the Python Imaging Library, used for opening, manipulating, and saving images.
  sklearn.preprocessing.label_binarize: Used for converting labels into a binary array (for multi-label classification).
  sklearn.metrics.confusion_matrix: Computes the confusion matrix to evaluate the accuracy of a classification.
  sklearn.model_selection.train_test_split: Used to split arrays or matrices into random train and test subsets.
Keras Libraries:
  keras: An open-source software library that provides a Python interface for artificial neural networks.
  keras.utils.np_utils.to_categorical: Converts class vectors (integers) to binary class matrices (one-hot encoding).
  keras.models.Sequential: A linear stack of layers.
  keras.layers: A module that contains the various layers used in a model.
    Dense: A fully connected layer.
    Dropout: A layer that randomly sets a fraction of input units to 0 at each update during training time.
    Flatten: Flattens the input.
    Conv2D: A 2D convolution layer.
    MaxPool2D: A max pooling operation for 2D spatial data.
    BatchNormalization: Normalizes the inputs of the layer.
keras.backend: A module that provides a generic interface for Keras, regardless of which deep learning framework is used as a backend (TensorFlow, Theano, etc.).
keras.optimizers.Adam: An optimizer that implements the Adam algorithm.
keras.preprocessing.image.ImageDataGenerator: Generates batches of tensor image data with real-time data augmentation.
keras.callbacks.ReduceLROnPlateau: A callback that reduces the learning rate when a metric has stopped improving.
