# Predicting Drug Resistance in Malaria Using Language Models

## Introduction

## Methods

### Dataset

### Model Architechture

### Training and Fine-Tuning

### Correlation between mutations and drug resistance

## Results
We trained several models, a selection of which can be seen in the table. Our models that are labeled as being large were trained off approximately 80% of our training data, approximately 36000 pieces of data while the small models were trained for fewer epochs from 2000 pieces of data. We were able to achieve a 40% accuracy with our large models and a 99% accuracy with our small model.

Each of these models have the ability to produce a series of probabilities that represent the likelihood of a nucleotide for each position in a sequence. By grabbing the maximum probability for each position, we get a prediction for what nucleotide we think should occupy that position. In the case shown by the figures below, for positions 20-29 of the sequence we predict the input sequence to be \"CCCCCCAAAC\". 


## Conclusion/Discussion
To conclude, we were able to create a model that learned what, at a baseline, malaria should look like. Continuing off of this research, we hope that this model can take in new incoming sequences of malaria from the same species as the baseline in order to observe how accurately the model is able to guess what the new DNA sequence looks like with low accuracy possibly corresponding to DNA mutations that may cause drug resistance. Additionally since the model makes a prediction at each nucleotide position, the model may even be able to pinpoint where the DNA sequence has mutated.

In the future, we hope that this can mean that we are not only able to detect mutations in malaria sooner, thereby starting new drug and medication research earlier, we can also help pinpoint how medication needs to change through locating where in a sequence of DNA has low predictability, thereby locating where the DNA has likely changed and what about the DNA sequence may be causing higher drug resistance. Additionally, although we trained our model off of Malaria data, this model can be trained off of any type of data which means it may be able to be fine-tuned to other types of diseases. In the end, by calculating accuracy and by extension the predictability of new DNA sequences we hope that our model will be able to decrease the amount of time it takes to create new effective medication for malaria, thereby decreasing the amount of deaths caused by malaria.


## Appendix

## Contributions

### References