# Beer Data Analysis

The project aims to implement distributed data mining algorithms on a large dataset using [PySpark](https://spark.apache.org/docs/latest/api/python/ "PyPsark documentation"), a Python API for Apache Spark, to learn how to handle big data. To do so, we choose a dataset from Kaggle and run some clustering and classification algorithms.

## Project info
This project was realized in collaboration with my colleagues: 
* [Federico Volpi](https://www.linkedin.com/in/federico-volpi-53875b194/ "Linkedin profile"), 
* [Simona Sette](https://www.linkedin.com/in/simona-sette-34a26b23b/ "Linkedin profile"), 
* [Pierluigi Basile](https://www.linkedin.com/in/pierluigi-brasile-645b841b5/ "Linkedin profile"), 
* Marco Mannarà

First, we did a data exploration, understanding and preparation phase to analyze the dataset and prepare it for the subsequent tasks.

Next, for the clustering phase, we tested two algorithms, k-means and bisecting k-means. For both of the clustering techniques, we analyzed the goodness of the silhouette score with different numbers of clusters.

After, we compare the performance of the best result for each method. Then, for the classification, instead, we did both a multiclass classification task and a binary one. In the multiclass one, we used the Random Forest classifier and the Logistic Regression, and for the binary one, the Gradient Boosting and the Naive Bayes Classifier. Finally, we implement a sentiment analysis with an NPL-based binary classification with [Spark NPL](https://nlp.johnsnowlabs.com/) using the Naive Bayes Classifier.

Please see the [report](https://github.com/The-Saba/Beer-Data-Analysis/blob/main/Report.pdf) and the [code](https://github.com/The-Saba/Beer-Data-Analysis/blob/main/Beer%20Data%20Analysis.ipynb) for a more detailed description.

The project is part of the Distributed Data Analysis and Mining exam of the [Data Science and Business Informatics](https://didattica.di.unipi.it/en/master-programme-in-data-science-and-business-informatics/) master's degree course at the University of Pisa.

## Data source
* Kaggle - [Beer Data Analytics](https://www.kaggle.com/datasets/gauravharamkar/beer-data-analytics "Kaggle dataset")
