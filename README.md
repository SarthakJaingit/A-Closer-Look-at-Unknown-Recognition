# A-Closer-Look-at-Unknown-Recognition

[[Paper]](A_Closer_Look_at_Unknown_Recognition.pdf)

Sarthak, Shu

In this repo, I researched the performance of OpenGAN and MaxLogits on a variety of evaluation tasks. The notebooks above showcase the data-loading, training, and evaluation of these algorithms. 

**Abstract:**
Computer Vision models often face imagery data that is from unknown classes that are not seen in the training set. To recognize such unknown images, previous research has created algorithms that exploit labeled data w.r.t $K$ categorical classes. In particular, the state-of-the-art method MaxLogits uses the maximum value of the logits to measure the open-set likelihood, while OpenGAN learns a discriminator as the open-set likelihood function by learning with generated fake open-set training data. In our paper, we compare OpenGAN and MaxLogits in scenarios that we have large and small numbers of classes. We then study their performance on three different types of unknown data: Gaussian noise, uniform noise, heavily-perturbed images, unseen images from other datasets. Experiments show that OpenGAN outperforms MaxLogits in almost all unknown types.

Jain Sarthak

jainsarthak101@gmail.com
