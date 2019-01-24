# Brain Tumour Segmentation

I have implemented the Code using Keras
Data Set will be using the Brat Data Set - https://www.smir.ch/BRATS/Start2013

## GPU
Will be using the Google Colabs for accessing powerfull GPUs

## Code author
This code belongs to Jagadish Sivakumar , developed in reference with the Jadevaibhav's Keras code, Each section of whole code is individually fragmented.

## Resources
The whole reference paper that is used in this development is https://arxiv.org/pdf/1505.03540.pdf

## Changes
 - The reference paper uses two-way training process but in the code 'weighted-categorical-loss' function for which weights are calculated per slice basis.
 - Batch normalizations is used instead of dropouts, it smoothens optimization curve.
 ![](batch1.png)
 ![](batch2.png)
