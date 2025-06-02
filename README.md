# Project Name: Disease_Treatment_Identification_Assignment

## General Information

### Project Information

> This assignment is meant to understand the application of Name Entity Recognition or NER in healthcare.

### Project Background

- A health tech company called ‘BeHealthy’ aims to connect the medical communities with millions of patients across the country. 
 
- ‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.
 
- So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

### Project Description

- In the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, for example, the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence.
- Note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but you can build an algorithm to map the diseases and their respective treatment.
- Determine the disease name and its probable treatment from the dataset and list it out in the form of a table or a dictionary.

### Data Set

> The data set for the Assignment consists of:
- train_sent
- test_sent
- train_label
- test_label
> The train dataset is used to train the CRF model, and the test dataset is used to evaluate the built model.
> Each word in dataset is provided in a single line. So, first, all these words needs to be clubbed together to form the sentences. There are blank lines given in the dataset that  indicate that a new sentence is starting from the next line onwards to the next blank line.
> There are three labels that have been used in this dataset: O, D and T, which are corresponding to ‘Other’, ‘Disease’ and ‘Treatment’, respectively.
> These labels correspond to each word that is available in the ‘train_sent’ and 'test_sent' datasets. So, there is one-to-one mapping of each label available in the 'train_label' and 'test_label' datasets with the words that are available in the 'train_sent' and 'test_sent' datasets, respectively.

### Assignment Steps

- process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
- After that, define the features to build the CRF model.
- Then, apply these features in each sentence of the train and the test dataset to get the feature values.
- Once the features are computed, define the target variable and then build the CRF model.
- Then, perform the evaluation using a test data set.
- After that, create a dictionary in which diseases are keys and treatments are values.

### Tasks

- Data preprocessing
- Concept identification
- Defining the features for CRF
- Getting the features words and sentences
- Defining input and target variables
- Building the model
- Evaluating the model
- Identifying the diseases and predicted treatment using a custom NER


## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [@sumishra-git] - feel free to contact me!

<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.
