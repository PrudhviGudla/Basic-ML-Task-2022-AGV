# Basic-ML-Task-2022-AGV
I studied from the slides of the MLFA class, made handwritten notes, did the andrewng course: https://www.coursera.org/learn/machine-learning and covered the topics : 

Supervised Learning
1) Linear regression and its objective function
2) Non linear regression
3) Locally weighted regression and its objective function
4) K- nearest neighbour, distance weighted KNN, scale effects, attributes, Value Difference Metric
5) Condensed KNN
6) Logistic Regression, likelihood function, gradient ascent
7) Gradient descent for logistic regression : BGD
8) Stochastic GD
9) Mini batch SGD
10) Adagrad: adaptive GD
11) Adaptive Moment Estimation(ADAM)
12) Vectorization
13) Feature scaling
14) regularization

Deep Neural Network
1) Structure of DNN
2) Components of DNN
3) Ingredients of DNN

Some other important info i found are in this doc : https://docs.google.com/document/d/1w4DW1VRIc8x0MaTGtCiOajWcWNhoNkx96KUmsmG43ck/edit?usp=sharing

Now I am currently learning python for machine learning from IITG.ai course : https://machinelearning-ai.netlify.app/
will refer to the Applied Machine Learning in Python course when necessary : https://www.coursera.org/learn/python-machine-learning?specialization=data-science-python#syllabus
I will also watch these lectures, Stanford CS229: https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU
Currently I am studying Python implementation of ML from my MLFA lab : link to the jupyter notebooks we use: https://drive.google.com/drive/folders/1cWOtk1R1riRWV2_FEQ1JO80-rXvySU2S?usp=sharing

## Kaggle challenge task
https://www.kaggle.com/c/digit-recognizer/overview

### Problems faced : 
1) I downloaded the csv files from the website and was trying to access them,
then I faced the error : 
```bash
'function' object is not subscriptable
```
Then I got to know that my file should be in the same directory as my jupyter file iam working on or
i would have to specify the path to the file

Then I faced an error : 
```bash
(unicode error) 'unicodeescape' codec can't decode bytes in position 2-3: truncated \UXXXXXXXX escape
```
Then I found solution in this website : https://stackoverflow.com/questions/37400974/unicode-error-unicodeescape-codec-cant-decode-bytes-in-position-2-3-trunca
![image](https://user-images.githubusercontent.com/106007058/188130928-b7469d55-a2a1-4b35-952a-e31f7f17445a.png)

2) other problems i faced are when creating the csv file to be submitted in kaggle
i referred to these websites : https://www.pythontutorial.net/python-basics/python-write-csv-file/
https://www.geeksforgeeks.org/how-to-append-pandas-dataframe-to-existing-csv-file/

### What I did :
1) I split the training data into inputs and labels  
2) I used KNN classifier with 3 neighbours
3) I predicted the outputs for the test data using the model 
4) appended this data into the csv file
5) submitted it in kaggle
6) I got the accuracy of 0.96803 and leaderboard position of 835
