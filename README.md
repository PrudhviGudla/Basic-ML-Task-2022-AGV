# Basic-ML-Task-2022-AGV

ML and DL specialisation by Andrew Ng in Coursera is very good course for beginners.
 https://www.coursera.org/learn/python-machine-learning?specialization=data-science-python#syllabus
Another ueful course: https://machinelearning-ai.netlify.app/

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
