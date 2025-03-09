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
Drug resistance in malaria, specifically in the species Plasmodium falciparum which we attempted to analyze through this experiment, has exploded in recent decades leading to a resurgence of malaria and millions of deaths, especially in children. This can largely be attributed to not only an overuse of medication, but more importantly for this study, genetic mutation.

By attempting to create a model that can learn what, at a baseline, malaria should look like, we hope that we can pinpoint if new specimens of Plasmodium falciparum are drug resistant. This is done by seeing how accurately the model can guess what the new sequence should look like, having been trained off of the current idea of Plasmodium falciparum, with low accuracy predictions possibly corresponding to DNA mutations that cause drug resistance. Additionally, since the model makes a prediction at each nucleotide position, the model may even be able to pinpoint where the DNA sequence has mutated.

In the future, we hope that this can mean that we are not only able to detect mutations in malaria sooner, thereby starting new drug and medication research earlier, we can also get a better idea of how medication needs to change through locating where in a sequence of DNA has low predictability, thereby locating where the DNA has likely changed and what about the DNA sequence may be causing higher drug resistance. 

For example, Patrick G Bray et al. in “Defining the role of PfCRT in Plasmodium falciparum chloroquine resistance” discusses how a specific protein leads to resistance of chloroquine, a common drug that was used in antimalarial medication. It is our hope that our model would be able to track changes in this protein and other proteins present, to get a better understanding of how and why drug resistance may be rising in malaria and how researchers may need to change current antimalarial medication to better target this new form of malaria. 

Additionally, although we trained our model off of Malaria data, this model can be trained off of any type of data which means it may be able to fine-tune to other types of diseases. In the end, by calculating accuracy and by extension the predictability of new DNA sequences we hope that our model will be able to decrease the amount of time it takes to create new effective medication for malaria, thereby decreasing the amount of deaths caused by malaria.


## Appendix

## Contributions

### References