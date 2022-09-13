# Land-Classification-in-Satellite-Images-by-Injecting-Traditional-Features-to-CNN-Models
Land Classification in Satellite Images by Injecting Traditional Features to CNN Models Paper Repository
First of all, I would like to special thanks to my professeurs and supporters.

Beril Sirmacek b.sirmacek@saxion.nl and Cem Unsalan cem.unsalan@marmara.edu.tr

# Abstract 

Deep learning methods have been successfully applied to remote sensing problems for several years. Among these methods, CNN based models have high accuracy in solving the land classification problem using satellite or aerial images. Although these models have high accuracy, this generally comes with large memory size requirements. On the other hand, it is desirable to have small-sized models for applications, such as the ones implemented on unmanned aerial vehicles, with low memory space. Unfortunately, small-sized CNN models do not provide high accuracy as with their large-sized versions. In this study, we propose a novel method to improve the accuracy of CNN models, especially the ones with small size, by injecting traditional features to them. To test the effectiveness of the proposed method, we applied it to the CNN models SqueezeNet, MobileNetV2, ShuffleNetV2, VGG16, and ResNet50V2 having size 0.5 MB to 528 MB. We used the sample mean, gray level co-occurrence matrix features, Hu moments, local binary patterns, histogram of oriented gradients, and color invariants as traditional features for injection. We tested the proposed method on the EuroSAT dataset to perform land classification. Our experimental results show that the proposed method significantly improves the land classification accuracy especially when applied to small-sized CNN models.

# How to Run the Code?

First of all, you need to get the eurosat dataset from the Kaggle via:
https://www.kaggle.com/datasets/apollo2506/eurosat-dataset
or
https://www.kaggle.com/datasets/ryanholbrook/eurosat

My notebook uses directly the data from my drive. So that if you do not want to modify the code, you can add the eurosat data on your drive and link your drive into the your notebook or you can trace the steps "how to get data from Kaggle dataset?"

Afterwards, you can click the run on the "Dataset Prepration" and please go step by step. Each block uses elder blocks.

And you can ask me if the Jupyler failing. 

Best,
