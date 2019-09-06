# StarGAN

## Description

The Keras impletation of the StarGAN.

## Example

![Sample_Epoch_No_7_Batch_No_2500](https://github.com/whpen/StarGAN-Keras/blob/master/assets/Sample_Epoch_No_7_Batch_No_2500.png)

## Image Dataset

[CelebA Image Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html "CelebA Image Dataset")

## Note for the code

* list_attr_celeba.txt:  The attribute file, containing one-hot encoding for each image. The dimension of label is 40. 
* Image data used : in the dataset folder: CelebA\Img\img_align_celeba
* classification loss weight: set to 5 rather than 1 comparing with original paper



## Reference paper

[StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation](https://arxiv.org/pdf/1711.09020.pdf)

