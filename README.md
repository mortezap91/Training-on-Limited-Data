# Training-on-Limited-Data

In this repository, I explored strategies for working with limited data by training a model on two classes of the CIFAR-10 dataset using 25 random instances, then averaging the results. I identified two effective approaches for handling small datasets:

1. Applying data augmentation to expand the dataset and avoid training complex networks from scratch. I used both an ensemble model and data augmentation to address this challenge.
2. Combining transfer learning with data augmentation to achieve higher accuracy.


I tested these approaches on all 10 classes of the CIFAR-10 dataset, and as demonstrated, the accuracy significantly improves when using transfer learning.
