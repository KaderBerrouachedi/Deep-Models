Deep Parallel ExtraTrees Is Here!
========
This is the official clone for the implementation of Deep Parallel ExtraTrees .

This package is provided "AS IS" and free for academic usage. You can run it at your own risk. For other purposes, please contact Prof. Rakia JAZIRI <rakia.jaziri@univ-paris8.fr>

                                       
Requirements: This package is developed with Python 2.7, please make sure all the dependencies are installed,
which is specified in requirements.txt 

ATTN: This package was developed and maintained by Jaziri Rakia , Gilles Bernard, Berrouachedi Abdelkader .For any problem concerning the codes, please feel free to contact Mr.Berrouachedi.（a.berrouachedi@yahoo.fr , <abdelkader.berrouachedi@etud.univ-paris8.fr> ).


Supported Based Classifier
=====================

* ExtraTreesClassifier


Supported Data Types
=====================
  ### If you wish to use Cascade Layer only, the legal data type for X_train, X_test can be:
  *   2-D numpy array of shape (n_sampels, n_features).
  *   3-D or 4-D numpy array are also acceptable. For example, passing X_train of shape (60000, 28, 28) or (60000,3,28,28) will be automatically be reshape into (60000, 784)/(60000,2352).


  ### If you need to use Finegraind Layer, X_train, X_test MUST be a 4-D numpy array
  * for image-like data. the dimension should be (n_sampels, n_channels, n_height, n_width)
  * for sequence-like data. the dimension should be (n_sampels, n_features, seq_len, 1). e.g. For IMDB data, n_features is 1. For music MFCC data, n_features is 13.


package dependencies
========
The package is developed in python 2.7

run the following command to install dependencies before running the code:
```pip install -r requirements.txt```



Happy Hacking.
