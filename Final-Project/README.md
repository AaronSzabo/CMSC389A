Improving the quality of white wine with neural networks<br>
By: 			Aaron Szabo<br>
Last Updated: 	5/17/2018<br>

Overview
-
The purpose of this project is to create a model that accurately predicts the quality of a white wine based off of 11 given characteristics and then to use that model to determine the optimal changes to maxmize the possibly quality of a given wine. 

Requirements
-
Keras with tensorflow backend<br>
Numpy<br>
Panda<br>
sklearn<br>

Data
-
The data file used can be downloaded from: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv<br>
Courtesy of:P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.<br>
Modeling wine preferences by data mining from physicochemical properties.<br>
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.<br><br>
The file needs to be put in the same location as the jupyter notebook

Running the code
-
To run the code, run each code cell in order. If you would like to test different accuracy ranges, there is a range variable <code>rng</code> in the <b>Evaluating the Model</b> section. To use the application, enter an integer in the range given and the program will output the optimal changes to the wine at the given index in the test data. Currently this is no support for testing custom wines. 

Video
-
Linked is a video presentation of the project:
https://youtu.be/RtCpDJp5208

Optimization
-
The Data spreadsheet contains a record of the different architectures that were tested prior to the current model being selected. Of note, all of the models typically had an accuracy of 60%-75% on the 1/4 range and 45%-55% on the 1/6 accuracy. The data sheet consists of the number of ndoes and their activation type for each layer. The right columns record the accuracy for the specified ranges. The <code>(500)</code> signifies accuracies with models trained over 500 epochs. The rest were trained on 100 epochs. 