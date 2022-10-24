# Demystify-the-Unknowns

Sarthak, Shu

In this repo, I researched the performance of OpenGAN and MaxLogits on a variety of evaluation tasks. The notebooks above showcase the data-loading, training, and evaluation of these algorithms. 

**Abstract:**
Computer Vision models will often face image data that is out-of-distribution from its train set. Coined as Open-Set Recognition, previous research has created algorithms that exploit K-way classification to classify such out-of-distribution images. 1) MaxLogits utilizes the values obtained from the final nodes of trained CNN classifier while 2) OpenGAN generates its own fake data to train a discriminator that can focus on the features of an image. In our paper, we train OpenGAN and MaxLogits when K=180 and when K=6. We then study the performance of these four models on 3 different types of out-of-distribution data. We find that OpenGAN outperforms MaxLogits in the Gaussian/Uniform Noise and Noise as Unknown Evaluations although the difference in AUPR and AUROC is wider when K=180. For Cross-Dataset Evaluation, OpenGAN again outperforms MaxLogits when the out-of-distribution set is SVHN or EuroSAT, but when it is MNIST, MaxLogits performs better. 


Jain Sarthak

jainsarthak101@gmail.com
