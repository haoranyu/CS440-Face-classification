CS440-Face-classification
=========================
Naïve Bayes Classifier is a widely used classification scheme, which is based on Bayes’ Theorem.We were given a dataset of 451 training examples and 150 test examples of face images and the corresponding labels (1 indicates face, 0 indicate not face).

Data-preprocessing
=========================
Convert each ‘pixel’ like face image into a vector of features. In the training sample file, there are 451 pixel images of handwriting digit of size 68*60. We convert each ‘pixel’ of ‘#’ to numerical value 1 and space ‘ ’ to numerical value 0 and thus build a vector of dimension 4080 (=68*60) with binary values for each example. 

Training and Testing
=========================
Count           Face  !Face
Predict - Face    70  7
Predict - !Face   10  63	

With total of 150 examples, total number of correctly classified example: 133 , with correct ratio: 0.88667

Team & Copyright
=========================
COPYRIGHT CS440 Group @ University of Illinois at Urbana-Champaign By Haoran Yu, Le Wang and Tao Feng
