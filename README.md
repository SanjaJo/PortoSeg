# PortoSeg
Feature selection and classification

## Getting started
This project was developed and executed in Jupyter notebook as part of a thesis. Goal of the thesis was to explore and analyze several feature selection and classification methods. The dataset was published on Kaggle and can be accessed at https://www.kaggle.com/c/porto-seguro-safe-driver-prediction

## Prerequisites
The kernel was run in the personal kernel on Kaggle. When run locally, python packages need to be installed - pip can be used(for further details https://packaging.python.org/tutorials/installing-packages/). It is also required to download the dataset and load them into your notebook and change it to a local path. 

## Running
Until the headline feature selection, the entire code can be executed. Then it needs to be executed according to the selected feature selection method as there are 4 different methods. 
You first need to run the selected features and then you need to delete it from the dataset (see the head line Drop the selected features).
1) Feature selection using variance threshold.
2) Feature selection using random forest.
3) Feature selection using Weka datamining tool (forward selection).
4) Feature selection using Weka datamining tool (backward selection).

Some models might take up a time to be executed - keep in mind. 


## Acknowledgements
Bert Carremans https://www.kaggle.com/bertcarremans/data-preparation-exploration.
Daniel Haden https://www.kaggle.com/hadend/tuning-random-forest-parameters.
https://www.fabienplisson.com/choosing-right-features/.
Olivier https://www.kaggle.com/ogrellier/noise-analysis-of-porto-seguro-s-features.
Chris Albon https://chrisalbon.com/machine_learning/trees_and_forests/feature_selection_using_random_forest/

#not used for written analysis but still included in notebook
HyungsukKang https://www.kaggle.com/sudosudoohio/stratified-kfold-xgboost-eda-tutorial-0-281
