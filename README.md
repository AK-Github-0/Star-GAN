# Star-GAN
This repository contains implementation of StarGAN using PyTorch. I have made a well commented and easy model of star gan implemented on CelebA dataset. CelebA dataset contains more than 200,000 images so I only chose 12000 images for training. It contains around 40 facial atttributes like hair colour, nose size but I have chosen only 19 attributes. I have made well defined area for selecting atttributes so one can choose any kind of attributes. The images size for training can also be increased if one has enough computational resources by few changes in the data loading function.
I took help from the research paper for star gan, cited in the end. 
(@inproceedings{choi2018stargan,
author={Yunjey Choi and Minje Choi and Munyoung Kim and Jung-Woo Ha and Sunghun Kim and Jaegul Choo},
title={StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation},
booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
year={2018}
} 
