# One2MFusion Multi-model for AD Detection from Gene Expression Dataset
A New Approach for Multimodal Usage of Gene Expression and Its Image Representation for the Detection of Alzheimer’s Disease

#Abstract:

Alzheimer's disease (AD) is a complex neurodegenerative disorder and the multifaceted nature of it requires innovative approaches that integrate various data modalities to enhance its detection. However, due to the cost of collecting multimodal data, multimodal datasets suffer from an insufficient number of samples. To mitigate the impact of a limited sample size on classification, we introduce a novel deep learning method (One2MFusion) which combines gene expression data with its corresponding 2D representation as a new modality. The gene vectors were first mapped to a discriminative 2D image for training a Convolutional Neural Network (CNN). In parallel, the gene sequences were used to train a feed-forward neural network (FNN) and the outputs of FNN and CNN were merged, and a joint deep network was trained for binary classification of AD, Normal Control (NC) and mild cognitive impairment (MCI) samples. The fusion of gene and gene-originated 2D image increased the accuracy (Area Under Curve) from 0.86 (obtained by 2D image) to 0.91 for AD vs. NC and from 0.76 (obtained by 2D image) to 0.88 for MCI vs. NC. The results show that representing the gene expression in another discriminative form increases the classification accuracy when fused with base data.

#Keywords: data fusion; dementia; deep learning; multimodal; Alzheimer’s disease; linear discriminant analysis 


![MergedModel3](https://github.com/akkayaumit/One2MFusion-MultiModel-AD_DetectionModel/assets/119974819/bb9465e6-c59d-4002-88db-1a6bdb4d6764)
