## Syntactic Processing Assignment: Identifying Entities in Healthcare Data

## Table of Contents
* [Problem Statement](#problem-statement)
* [Dataset Details](#dataset-details)
* [Objectives](#Objectives)
* [Conclusion(Inferences)](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

### Problem Statement
‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.
So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day

### Dataset Details

There are four datasets provided to process, which are as follows: 
- train_sent.
- test_sent.
- train_label.
- test_label.

### Objectives
 Build a custom NER to get the list of diseases and their treatment from the dataset.

1. You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
2. After that, you need to define the features to build the CRF model.
3. Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
4. Once the features are computed, you need to define the target variable and then build the CRF model.
5. Then, you need to perform the evaluation using a test data set.
6. After that, you need to create a dictionary in which diseases are keys and treatments are values.


There are eight major tasks that you need to perform to complete the assignment. They are as follows:
1. Data preprocessing
2. Concept identification
3. Defining the features for CRF
4. Getting the features words and sentences
5. Defining input and target variables
6. Building the model
7. Evaluating the model
8. Identifying the diseases and predicted treatment using a custom NER

![image](https://github.com/abhijit12banerjee/Healthcare_SyntacticProcessing/assets/107828454/2d98246e-b24c-460b-8409-271b24a3f8e3)

## Conclusion(Inferences)
 - Treatment for desease 'hereditary retinoblastoma' is 'radiotherapy'.
 - Treatment for 'autoimmune hemolytic anemia' are 'heparin'.
 - Treatments for 'advanced stage ( tnm iib-ivb ) mycosis fungoides' are 'a combination chemotherapy program consisting of bleomycin and methotrexate weekly , doxorubicin every'.
 - Drawing upon the findings outlined above, it is evident that the it consistently yields precise results when querying for specific diseases.

## Technologies Used
- Python
- Matplotlib
- Seaborn
- Numpy
- Pandas
- pycrf
- scikit-learn
- spacy
- nltk
- sklearn-crfsuite

## Acknowledgements

- https://colab.google/
- https://www.sciencedirect.com/topics/computer-science/syntactic-processing#:~:text=2%20Syntactic%20Processing,Bridge%20flying%20to%20San%20Francisco.
- https://www.ibm.com/topics/named-entity-recognition

## Contact

Created by [@geek-bhuvnesh] feel free to contact me!