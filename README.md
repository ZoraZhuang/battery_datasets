# battery_datasets

This repository contains two battery data sets used in the paper "Property Prediction for Complex Compounds
Using Structure-free Mendeleev Encoding and Machine Learning":

1. A computational data set, which consists of 10129 instances of battery compounds that were simulated using
electronic structure methods, extracted from the Materials Project online database. The data set was obtained using both the legacy and the new APIs. The computational data set (`mp_total.csv`), along with the notebooks that extracts and processes the data, are provided here in the `computational` folder.

2. An experimental data set consisting of 254749 batteries extracted from the literature. Originally collected and published by [Huang and Cole](https://doi.org/10.1038/s41597-020-00602-2), it was then preprocessed and cleaned in preparation for subsequent machine learning tasks. The notebook that processes the data set are provided along with the processed data in the `experimental` folder. There are several versions of the cleaned data set, each representing a different degree of data cleaning and pruning. In our research, we used the cleanest data set `batteries_ultra_cleaned.csv`.

