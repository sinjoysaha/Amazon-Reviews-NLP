# Amazon Review Classification using NLP

[![GitHub contributors](https://img.shields.io/github/contributors/sinjoysaha/Amazon-Reviews-NLP.svg)](https://GitHub.com/sinjoysaha/Amazon-Reviews-NLP/graphs/contributors/)
[![GitHub forks](https://img.shields.io/github/forks/sinjoysaha/Amazon-Reviews-NLP.svg)](https://GitHub.com/sinjoysaha/Amazon-Reviews-NLP/network/)
[![GitHub stars](https://img.shields.io/github/stars/sinjoysaha/Amazon-Reviews-NLP.svg)](https://GitHub.com/sinjoysaha/Amazon-Reviews-NLP/stargazers/)
[![GitHub watchers](https://img.shields.io/github/watchers/sinjoysaha/Amazon-Reviews-NLP.svg)](https://GitHub.com/sinjoysaha/Amazon-Reviews-NLP/watchers/)
[![GitHub issues](https://img.shields.io/github/issues/sinjoysaha/Amazon-Reviews-NLP.svg)](https://GitHub.com/sinjoysaha/Amazon-Reviews-NLP/issues/)
[![Profile views](https://gpvc.arturio.dev/sinjoysaha)](https://GitHub.com/sinjoysaha/)
[![GitHub followers](https://img.shields.io/github/followers/sinjoysaha.svg)](https://github.com/sinjoysaha?tab=followers)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&color=545454)](https://linkedin.com/in/sinjoysaha)
[![Twitter](https://img.shields.io/badge/-Twitter-blue.svg?style=flat-square&logo=twitter&color=b3e0ff)](https://twitter.com/SinjoySaha)

## Table of Contents

* [About the Project](#about-the-project)
  * [Steps](#steps)
  * [Built With](#built-with)
* [Fork the Repo and Contribute](#Fork-the-Repo-and-Contribute)
* [Contact](#contact)

## About the Project

In this [`Classification Project`](https://github.com/sinjoysaha/Amazon-Reviews-NLP), we use Natural Language Processing techniques and different Machine Learning models to classify Amazon book reviews into `POSITIVE` or `NEGATIVE` sentiments. 

[![Project Image](docs/images/Amazon-Reviews-NLP-projectimage.png)](https://github.com/sinjoysaha/Amazon-Reviews-NLP)

### Tasks

1. Bag of Words technique was used to vectorized the reviews using the CountVectorizer (binary only) and TfidfVectorizer (Term Frequency - Inverse Document Frequency). 

2. Since the smaller dataset was imbalanced, we use a bigger dataset and balance out the `POSITIVE`s and `NEGATIVE`s.

3. The models that were compared are as follows:
    - Linear SVM
    - Decision Tree
    - Naives Bayes
    - Logistic Regression

4. Further, GridSearchCV was used to find the best parameters for the Linear SVM model. 

5. The model is stored using the Pickle library. 

6. In future, rest of the models will be studied for finding best parameters of for each. An overall best performing model can then be found. 

### Built With

* Jupyter Notebook
* Scikit-learn
* Pickle
* Pandas
* json

## Fork the Repo and Contribute

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project (click on `Fork` in the top-left corner)
2. Create your Feature Branch (`git checkout -b feature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature`)
5. Open a Pull Request

## Contact

Sinjoy Saha 
  * [LinkedIn](https://linkedin.com/in/sinjoysaha)
  * [Twitter](https://twitter.com/SinjoySaha)