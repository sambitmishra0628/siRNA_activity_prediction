# Prediction of siRNA activity for RNA interference

## Description
The set of scripts included in this repository use the dataset of siRNA created by Heusken et. al (Heusken, Nature Biotechnology, 2005).
The goal is to develop, using this dataset, a regression model that will predict the efficacy of a given siRNA molecule for RNA interference and a classification model that will predict whether a given siRNA molecule will have the desired potency for RNA interference or not.

## Dataset
The dataset comprises of a set of guide RNA sequences from mouse and human and their measured activity against targetted mRNA sequences
![dataset](https://user-images.githubusercontent.com/6353495/63659005-dda59800-c77c-11e9-9494-6d907d832a5b.png)

## Approach
![approach](https://user-images.githubusercontent.com/6353495/63659212-11cd8880-c77e-11e9-92bc-14781a194884.png)

## List of features
The features were calculated using the calc_features_v2 script.
![feature_table](https://user-images.githubusercontent.com/6353495/63658806-7f2bea00-c77b-11e9-8ed0-63ceca92e029.png)




