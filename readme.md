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
* The training is 40 dims label. If only a few labels are considered, for example, 5 labels: ['Black_Hair','Blond_Hair','Brown_Hair','Male','Young'],then one solusion is to train the 40-label network at first, then concatenate extensions(5 input - 40 output, and 40 input - 5 output) on the pretrained model and train both pretrained model and extensions. The training with pretrained model is fast, taking less than 1 epoch. 



## Reference paper

[StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation](https://arxiv.org/pdf/1711.09020.pdf)

