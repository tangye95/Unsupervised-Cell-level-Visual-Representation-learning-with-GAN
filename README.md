# nu_gan
This repository contains the Python implementation for our paper *Unsupervised Learning for Cell-level Visual Representation in Histopathology Images with Generative Adversarial Networks* https://arxiv.org/abs/1711.11317. 

Requirements
=================
* Pytorch https://github.com/pytorch/pytorch
* HistomicsTK https://github.com/DigitalSlideArchive/HistomicsTK

Usage
=================

* Unsupervised Cell-level Classification:
```shell
python nu_gan.py --task 'cell_representation'
```

* Unsupervised Image-level Classification (**UNDER CONSTRUCTION**):
```shell
python nu_gan.py --task 'image_classification'
```
