# PruningModel_Tredence

The L1 regularization was applied internally in the training loop to optimize the accuracy and sparsity levels of the neural network, the CIFAR-10 consists of images of 10 different labels which consist of certain hidden features that are to be 
captured by the neural layer to assist in image classification. Each and every pixel is associated with a gradient and the relevance of the particular pixel determines whether the particular pixel/feature is to be pruned. The feature of L1 regularization
to constantly reduce the scores of the gate for every batch plays a role in L1 regularization increasing sparsity. The sigmoid function thereby recieves negative values that have been constantly regularized and therefore sparsity is encouraged while
using L1 regularization 

| Lambda (λ)              | Test Accuracy (%) | Sparsity Level (%) |
|------------------------|------------------|--------------------|
| 0.001                  | 41.17%           | 88.77%             |
| 0.002                  | 26.34%           | 98.44%             |
| 0.005                  | 10.00%           | 100.00%            |
| 0.01                   | 10.00%           | 100.00%            |



![Accuracy vs Number of Epochs](Test_Accuracy vs Epochs.png)
