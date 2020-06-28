# TP53 activity prediction: Machine Learning on TP53 dataset to predict mutants activity.
My finishing project for 6 months Sages Kodołamacz Data Science Bootcamp, which I was participating since November 2019.

## Project goal description

The goal of this project is to model mutant TP53 transcriptional activity (active vs inactive) based on data extracted from biophysical simulations in order to discover mutations that reactivate mutated TP53 found in human cancers.

This is an important biomedical goal because TP53 mutants have been implicated in half of all human cancers, and restoring active TP53 in tumors leads to tumor regression.

## Introduction

The TP53 gene encodes a tumor suppressor protein that is a key cellular defense against cancer. TP53 mutations occur in about 50% of human cancers. As demonstrated in vivo, TP53 cancer mutants can be reactivated through intragenic second-site suppressor (“cancer rescue”) mutations. Reactivated TP53 holds great therapeutic promise because animal models have shown that reintroduction of active TP53, even in advanced tumors, leads to tumor regression. Consequently, there have been many efforts to find small molecule drugs that mimic the cancer rescue effect of reactivating TP53 and suppressing tumor growth. Despite some promising discoveries in TP53 in specific, and small molecule docking in general, these efforts are hampered by a limited understanding of the p53 mutation-structure-function relationship. A larger and more diverse collection of cancer rescue mutations that reactivate TP53 cancer mutants is therefore desired. Such a collection could lead to insight into general structural changes that can rescue TP53 cancer mutants, and thereby facilitate rational drug design approaches by exploiting similar effects.

## Technologies

    python 3.7.4
    numpy
    pandas
    matplotlib
    scikit-learn

## Theories
    
    feature selection
    regularization
    logistic regression
    SVM
    random forest

## Attribute Information

There are a total of 5409 attributes per instance.
Attributes 1-4826 represent 2D electrostatic and surface based features.
Attributes 4827-5408 represent 3D distance based features.
Attribute 5409 is the class attribute, which is either active or inactive.
The class labels are to be interpreted as follows: 'active' represents transcriptonally competent, active p53 whereas the 'inactive' label represents cancerous, inactive p53. Class labels are determined experimentally.

More information is provided in the relevant papers cited.

## Relevant Papers

Danziger, S.A., Baronio, R., Ho, L., Hall, L., Salmon, K., Hatfield, G.W., Kaiser, P., and Lathrop, R.H. (2009) Predicting Positive p53 Cancer Rescue Regions Using Most Informative Positive (MIP) Active Learning, PLOS Computational Biology, 5(9), e1000498

Danziger, S.A., Zeng, J., Wang, Y., Brachmann, R.K. and Lathrop, R.H. (2007) Choosing where to look next in a mutation sequence space: Active Learning of informative p53 cancer rescue mutants, Bioinformatics, 23(13), 104-114.

Danziger, S.A., Swamidass, S.J., Zeng, J., Dearth, L.R., Lu, Q., Chen, J.H., Cheng, J., Hoang, V.P., Saigo, H., Luo, R., Baldi, P., Brachmann, R.K. and Lathrop, R.H. (2006) Functional census of mutation sequence spaces: the example of p53 cancer rescue mutants, IEEE/ACM transactions on computational biology and bioinformatics / IEEE, ACM, 3, 114-125. 

## Dataset can be downloaded below (p53_old_2010.zip)

https://archive.ics.uci.edu/ml/machine-learning-databases/p53/

Due to size of dataset it could not be uploaded.
