# Study and Experiments on Neural Networks and Clustering
- The [213070015_213079003_1.ipynb](https://github.com/213079003/EE769-IML/blob/main/Assignment3/213070015_213079003_1.ipynb) notebook deals with image classification using transfer learning of a ResNet-18 architecture that is pre-trained on a large dataset (ImageNet).
    - Finetuning this model to classify bees versus ants by varying learning rate and momentum. Then added weight decay for regularization, improving the testing accuracy from 94% to 96%.
    - Dataset: [link](https://download.pytorch.org/tutorial/hymenoptera_data.zip)
- In [213070015_213079003_2.ipynb](https://github.com/213079003/EE769-IML/blob/main/Assignment3/213070015_213079003_2.ipynb) notebook, preprocessed [data](https://github.com/213079003/EE769-IML/blob/main/Assignment3/DataClustering.csv) for clustering, chose the optimal value of k using Elbow and Silhouette methods, then trained and visualized the effect of k in k-means clustering using t-sne embedding.
- In [213070015_213079003_3.ipynb](https://github.com/213079003/EE769-IML/blob/main/Assignment3/213070015_213079003_3.ipynb) notebook, trained principal component analysis (PCA) on [data](https://github.com/213079003/EE769-IML/blob/main/Assignment3/DataPCA.csv) and selected the number of dimensions based on the variance explained.
  
- In [213070015_213079003_4.ipynb](https://github.com/213079003/EE769-IML/blob/main/Assignment3/213070015_213079003_4%20(3).ipynb) notebook, trained kernel principal component analysis (KPCA) on [data](https://github.com/213079003/EE769-IML/blob/main/Assignment3/DataKPCA.csv) and selected the number of dimensions based on the variance explained.

