# SemEval-Task6-CS408

## Offensive Tweets Classification - SemEval 2019 - Codalab Challenge

### Creator of Project :
Yagyansh Bagri


### Proposed Implementation : 
The Implementation proposed during this project relies on the GloVe word embedding, strong data processing and different networks such as Logistic Regression and Convolutional Neural Networks.

### Description of the Project :
The following description was taken on Codalab : [Link](https://competitions.codalab.org/competitions/20011#learn_the_details)

### Overall Summary of Research: 
Offensive language is pervasive in social media. Individuals frequently take advantage of the perceived anonymity of computer-mediated communication, using this to engage in behavior that many of them would not consider in real life. Online communities, social media platforms, and technology companies have been investing heavily in ways to cope with offensive language to prevent abusive behavior in social media..

In **OffensEval** we break down offensive content into three sub-tasks taking the type and target of offenses into account.

**Sub-tasks:**
1. **Sub-task A** - Offensive language identification
2. **Sub-task B** - Automatic categorization of offense types
3. **Sub-task C** - Offense target identification.

### Data: 
The data is retrieved from SemEval Task 6 Competition. The testing and traininga data are available in the "OLID_2019" tab. 

### Data Splitting & Exploratory Analysis:
Under this file we showcase how the OLID 2019 Dataset has been distributed and perform basic exploratory analysis.

### Pre-Processing Data:
Under this file we showcase how the OLID 2019 Dataset has been pre-processed and how users can replicate the methods to carry the techniques implemented on different datasets.

### Additional Baseline SVM:
Under this file we showcase the implementation of an additional Baseline technique we have implemented. The baseline performed is an SVM (Support Vector Machine) model.

### Random Forest Additional Baseline:
Under this file we showcase the implementation of an additional Baseline technique we have implemented. The baseline performed is a Random Forest model.


### Glove Vector Installation Stanford:
Under this file we showcase the addition and uploading of Glove Vectors that has been downloaded from Stanford University. The Glove Vectors that we use for our project are 100d and 200d. Users are recommended to try other Glove Vector dimensions as well to determin which Glove Vector is most suitable.


### Required Modules and Libraries:
Under this file we highlight the importance of downloading and importing the said libraries in order to execute the code correctly

### Logistic Regression Baseline 1:
Under this file we showcase our implementation of Logistic Regression as a baseline technique for the three different sub-tasks. Additionally for each subtask a Confusion Matrix, Classification Report and Results containing Macro F1-Score & Accuraccy has been provided.

### Description of the Content of this Repo: 
This repository contains the final submission of the project.

The report explaining the main steps and architectures of the network used
The Jupyter Notebook containing all the code for implementing and training the model.
