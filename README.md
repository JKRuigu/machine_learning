 ## Machine Learning

## Simple machine learning project using sklearn library

To get started you should have the following.

1. python installed [link](https://www.python.org/downloads/)  *I am using Python 2 to use python 3, add paranthesis for all the print statements*
   
2. sklearn installed ``pip install numpy scipy scikit-learn``

3. A text editor <br>
    Am using [Atom](https://atom.io/) make sure you have script package installed.To run script in atom just ``ctrl + shift + B``   
  
**Classifier Methods used** <br>
  * [Support Vector Machines](http://scikit-learn.org/stable/modules/svm.html) <br>
  * [Decision Tree Classifier ](http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html) <br>
  * [Random Forest Classifier](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)<br>

**HINT**:*Try to uncomment the some code to get the most out of it.*

Example:**How to change from one Classifier to another** *(Eg.From**svm** to **Random Forest Classifier**)* <br>

1. First we need to import **RandomForestClassifier** in a code by commenting out the code in ml.py file as follows <br>

**Before**

```python
  from __future__ import division
  from sklearn import datasets
  from sklearn import svm
  ## from sklearn import tree
  ## from sklearn.ensemble import RandomForestClassifier

```
**After**

```python
  from __future__ import division
  from sklearn import datasets
  ## from sklearn import svm
  ## from sklearn import tree
  from sklearn.ensemble import RandomForestClassifier
```

This enables us to import **Random Forest Classifier** to our code.

2.Link our classifier to use Random Forest Classifier

**Before**

```python
#Linking our Classifiers

    #SVM Classifier (default)
# clf = svm.SVC()
    #SVM defined
clf = svm.SVC(kernel='linear')

    # Tree Classifier
# clf = tree.DecisionTreeClassifier()
    #RandomForestClassifier
# clf = RandomForestClassifier()
  
```
 **After**
 
 ```python
 #Linking our Classifiers

    #SVM Classifier (default)
# clf = svm.SVC()
    #SVM defined
#clf = svm.SVC(kernel='linear')

    # Tree Classifier
# clf = tree.DecisionTreeClassifier()
    #RandomForestClassifier
clf = RandomForestClassifier()
 
 ```
 We have simply commented out ``clf = svm.SVC(kernel='linear')`` and uncommented ``clf = RandomForestClassifier()``
 
 3.Run the script,you should get the following, but can be with diffent figures 
 ```
 [1 2 0 1 2 0 0 2 0 0 1 0 2 1 0 1 2 1]
94.4444444444
[Finished in 0.668s]
 ```
 You have successfully used Random Forest Classifier. Try to use the Decision Tree Classifier following the same process.
## Support
- **Buy Me a cup of coffee** [link](https://buymeacoff.ee/UOoP6At7H) <br>
- **Give this page a star ): **
