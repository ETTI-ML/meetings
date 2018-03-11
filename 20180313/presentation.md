---
title: Meeting 1
subtitle: ETTI-ML Meetings
date: 13.03.2018
---

# Topics

1. Location / resources

2. Review: "Deep Learning for Computer Vision" 
    - Starter Bundle
    - Practitioner Bundle

3. GPU on the cloud: floydhub.com

4. Review: "Deep Image Prior"


# Location / resources

- Let's hold common stuff (presentations, paper etc.) in a common place

1. Github: https://github.com/ETTI-ML
    - Organization: ETTI-ML
    - Made a repository for meetings: https://github.com/ETTI-ML/meetings
    - Only public repositories for free accounts
    - Alternatives for private repos: gitlab.com,  bitbucket.com

2. Shared paper database: Zotero (zotero.com)
    - Keep a common database of papers, review notes, links etc.
    - A little cumbersome 
    - Alternatives: Mendeley, EndNote, Paperpile etc
 

# Review: "Deep Learning for Computer Vision" 

- Review: "Deep Learning for Computer Vision, With Python", Dr. Adrian Rosebrock, 1st Ed.

- Book + code examples + Virtual Machine

- Comes in three flavours:
    - Starter Bundle
    - Practitioner Bundle
    - ImageNet Bundle (not available)

# Review: "Deep Learning for Computer Vision" 

- Topic: Deep CNNs for image classification

- Style:
    - little theory
    - examples in Python, explained step by step

# Starter Bundle

- Starter Bundle
    - the easiest, contains the basics

- Topics:
    - Basics
        - Image classification basics
        - Basic datasets
        - Stochastic Gradient Descent
    - Neural Network basic architectures
        - Basic layer types
        - Backprop
        - CNN building blocks
        - Example: recognizing handwritten digits (MNIST) with LeNet 
    - Some tips & tricks: 
        - spotting underfiting / overfiting
        - checkpointing
        - visualize architectures

# Practitioner Bundle

- Practitioner Bundle
    - More advanced tips & tricks, but still easy from theoretic p.o.v.

- Topics
    - Advanced (state-of-the-art) CNN architectures for image classification: VGG, GoogLeNet, ResNet\
    - Adaptation: train / replace only top layers, keep pre-trained lower layers
    - Various alternatives to SGD (RMSprop etc)
    - More handy tips & tricks: data augmentation, preprocessing, work with HDF5 files
    - Works with larger datasets (Kaggle, subset of ImageNet)

# Side topics

- OpenCV is really for image processing
- This guy has a similar book for OpenCV: "Practical Python and OpenCV + Case Studies"


# GPU on the cloud: floydhub.com

- floydhub.com
- transfer code automatically to their site & run
- works with Jupyter notebooks (maybe also plain .py files)
- can be run / controlled from Linux command line (nice)
- affordable: Standard GPU, Tesla K80 with 12GB Memory, preemptible: 7$ / 10h
