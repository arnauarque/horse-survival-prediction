# Horse survival prediction

This repository contains the study, code, and results of the analysis of the Horse Colic Dataset. The objective of this project is to predict the survival of horses based on certain medical indicators using various Machine Learning methods.

## Authors and context

This project has been developed by the users [@arnauarque](https://github.com/arnauarque) and [@danielesquina](https://github.com/danielesquina) as part of the [Advanced Machine Learning](https://www.fib.upc.edu/en/studies/masters/master-data-science/curriculum/syllabus/AML-MDS) course in the [Master's in Data Science](https://www.fib.upc.edu/en/studies/masters/master-data-science) program at the [Faculty of Informatics of Barcelona](https://www.fib.upc.edu/en) (Universitat Politècnica de Catalunya). In this file, you can find an introduction to the project and its objectives. Additionally, you will find a detailed description of the repository's organization.

## Summary of the requirements

This project complies with the following requirements:

- Description of the work and its goals, the available data, and any additional information that you have gathered and used.
- Description of related previous work.
- Data exploration process.
- Reasoning of choice of the resampling protocol.
- Results obtained with each chosen method.
- Final model chosen and estimation of its generalization error.
- Scientific and personal conclusions.
- Possible extensions and known limitations.


## Description and objectives

For this course project we were required to choose a real world problem that motivated us. There was the possibility of carrying out a practical-oriented project or one with solid theoretical foundations. Given that one of the main objectives is to expand our knowledge in the field of Machine Learning, we have decided to undertake a project that combines the acquisition of theoretical and practical knowledge.

We selected the dataset known as the [Horse Colic Data Set](https://archive.ics.uci.edu/dataset/47/horse+colic), available in the UCI Machine Learning Repository. This dataset presents a multivariate challenge encompassing categorical, integer, and real attributes, comprising a total of 368 instances and 27 attributes containing missing values. These data records represent the medical conditions of horses that received treatment in various operating rooms throughout Canada. 

The primary objective of this problem revolves around predicting the outcome of the animal's medical intervention based on its characteristics and the values of the aforementioned medical indicators. Consequently, our task entails forecasting whether the horse survived, succumbed, or required euthanasia.

Read more in the [report](report.pdf) you can find in this repository.

## Repository organization

This repository is organized as follows: 

- The [code](code/) directory contains both the [original](code/data/) and [preprocessed](code/data/preprocessed/) datasets used in this project, along with the code for each of the required components:
    - [Data preprocessing](code/preprocessing.ipynb) (`Python`)
    - [Data visualization and clustering](code/visualization-clustering.ipynb) (`Python`)
    - [Classification with Support Vector Machines](code/svm.Rmd) (`R`)
    - [Data Analysis with Trees](code/dt-rf-classification.ipynb) (`Python`)
    - [Classification with KNN](code/knn-classification.ipynb) (`Python`)
    - [Classification with Logistic Regression](code/lr-classification.ipynb) (`Python`)
 - The [report.pdf](report.pdf) file contains a comprehensive introduction to the project, the established objectives, and the results and conclusions derived from the data analysis process. 
- The [annex.pdf](annex.pdf) file contains an annex with the description of each of the variables present in the utilized dataset.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository is licensed under the MIT License.



