# credit_risk

Files:
input: train.csv
code file: credit_risk.ipynb

Machine learning algorithm to predict whether a person taking loan is Risk(good/bad) based on previous other persons behavior 

### requirements
python 3.x
pip install sklearn                         --- sklearn framework
pip install pandas                          --- python pandas package
(or)
** Recomended Anaconda python 3.x distribution 

### Steps followed 
step-1 importing necessary libraries
step-2 standardizing the columns to get the values into same range as the Knn uses a distance based metric 
step-3 Used Multilabel encoder to label encode multiple columns to convert string category values columns into integer value columns as most of the algorithms only take integer categorical values 
step-4 Splitting the data into training and testing sets
step-5 Applying random forest and Knn algorithms
step-6 Evaluating the model using metrics like Precision, Recall, Fscore and accuracy  
step-7 Parameter tuning of the algorithms to improve the above metrics

#github link: https://github.com/harishakarapu/credit_risk

