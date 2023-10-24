### IFCB Quantification

#### Introduction
This dataset is based in the data available publicly at https://github.com/hsosik/WHOI-Plankton.

The scripts for the processing are available at https://github.com/pglez82/IFCB_Zenodo 

Basically, this is the IFCB dataset with precomputed features for testing quantification algorithms.

Samples from 2006 to 2008 (286 samples) are considered as training data for quantification algorithms.
Samples from 2009 to 2014 (678 samples) are considered as test bags for which the prevalence of the classes must be predicted.

The dataset has 50 classes (check the IFCB.test_prevalences.zip) to get a list of the observed classes.

Deep features have been computed using a resnet34 finetuned in the train data (using the labels). This results in 512 features which are available for all the samples in the dataset.

The label of each example is also available for all the train examples.
