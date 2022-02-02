## Dataset
Due to space limitations, it is not possible to make the dataset available here on Github. You can access it at: https://www.kaggle.com/zippyz/cats-and-dogs-breeds-classification-oxford-dataset

## Structure: this repository is divided into two parts
1 - breeds_classification, where the files referring to the binary classification for cat/dog are found; \
2 - species_classification, where the files referring to the categorical classification of breeds can be found (37 in all).

## Important technique used
In both cases, the transfer learning technique was used, which imports the pre-trained InceptionV3 network. This one showed a very good performance in both of the proposed problems, not being necessary to apply fine tuning at species_classification.

## Results
breeds_classification: 92.96% accuracy (test set) \
species_classification: 99.83% accuracy

## For more details, check the codes. Each step is commented and you can easily reproduce them
