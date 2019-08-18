# Adversarial_synthetic-zero-shot-Segmentation

## Adversarial data augmentation in semantic segmentation
### 1 SADA: Semantic Adversarial Diagnostic Attacks for Autonomous Applications
https://arxiv.org/pdf/1812.02132.pdf

(Object Detection)we re-frame the adversarial attack problem as learning a distribution of parameters that always fool the agent. In the semantic case, our proposed adversary (denoted as BBGAN) is trained to sample parameters that describe the environment with which the black-box agent interacts, such that the agent performs its dedicated task poorly in this environment.
### 2 Adversarially Tuned Scene Generation
https://arxiv.org/pdf/1701.00405.pdf

our work combines recent advances in CG, which aims at generating stochastic scene layouts using large collections of 3D object models, and generative adversarial training, which aims at training generative models by measuring discrepancy between generated and real data in terms of their separability in the space of a deep discriminatively-trained classifier. Our method uses iterative estimation of the posterior density of prior distributions for a generative graphical model. This is done within a rejection sampling framework. Initially, we assume uniform distributions as priors over parameters of a scene described by a generative graphical model. As iterations proceed the uniform prior distributions are updated sequentially to distributions that are closer to the unknown distributions of target data.
### 3 PIXEL LEVEL DATA AUGMENTATION FOR SEMANTIC IMAGE SEGMENTATION USING GENERATIVE ADVERSARIAL NETWORKS
https://arxiv.org/pdf/1811.00174.pdf

We propose using generative adversarial networks (GANs) to generate realistic images for improving the performance of semantic segmentation networks.

## Synthetic dataset for semantic segmentation
### 1 Learning Semantic Segmentation from Synthetic Data: A Geometrically Guided Input-Output Adaptation Approach
https://arxiv.org/pdf/1812.05040.pdf

we take the advantage of additional geometric information from synthetic data, a powerful yet largely neglected cue, to bridge the domain gap. Such geometric information can be generated easily from synthetic data and is proven to be closely coupled with semantic information. With the geometric information, we propose a model to reduce domain shift on two levels: on the input level, we augment the traditional image translation network with the additional geometric information to translate synthetic images into realistic styles; on the output level, we build a task network which simultaneously performs depth estimation and semantic segmentation on the synthetic data. Meanwhile, we encourage the network to preserve the correlation between depth and semantics by adversarial training on the output space.
### 2 Playing for Data: Ground Truth from Computer Games
https://arxiv.org/pdf/1608.02192.pdf

we present an approach to rapidly creating pixel-accurate semantic label maps for images extracted from modern computer games. Although the source code and the internal operation of commercial games are inaccessible, we show that associations between image patches can be reconstructed from the communication between the game and the graphics hardware. This enables rapid propagation of semantic labels within and across images synthesized by the game, with no access to the source code or the content
### 3 The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780721

we propose to use a virtual world to automatically generate realistic synthetic images with pixel-level annotations. Then, we address the question of how useful such data can be for semantic segmentation – in particular, when using a DCNN paradigm. In order to answer this question, we have generated a synthetic collection of diverse urban images, na`med SYNTHIA, with automatically generated class annotations. We use SYNTHIA in combination with publicly available real-world urban images with manually provided annotations. Then, we conduct experiments with DCNNs that show how the inclusion of SYNTHIA in the training stage significantly improves performance on the semantic segmentation task.
### 4 Virtual Worlds as Proxy for Multi-Object Tracking Analysis
https://arxiv.org/pdf/1605.06457.pdf

We propose an efficient real-to-virtual world cloning method, and validate our approach by building and publicly releasing a new video dataset, called “Virtual KITTI” 1 , automatically labeled with accurate ground truth for object detection, tracking, scene and instance segmentation, depth, and optical flow. We provide quantitative experimental evidence suggesting that (i) modern deep learning algorithms pre-trained on real data behave similarly in real and virtual worlds, and (ii) pre-training on virtual data improves performance. As the gap between real and virtual worlds is small, virtual worlds enable measuring the impact of various weather and imaging conditions on recognition performance, all other things being equal.
### 5 Sensor Transfer: Learning Optimal Sensor Effect Image Augmentation for Sim-to-Real Domain Adaptation
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8630027

we propose a learned augmentation network composed of physically-based augmentation
functions. Our proposed augmentation pipeline transfers specific
effects of the sensor model—chromatic aberration, blur, exposure,
noise, and color temperature—from a real dataset to a synthetic
dataset. We provide experiments which demonstrate that augmenting synthetic training datasets with the proposed learned augmentation framework reduces the domain gap between synthetic and
real domains for object detection in urban driving scenes.

## Zero-shot semantic segmentation
### 1 Zero-Shot Semantic Segmentation
https://arxiv.org/pdf/1906.00817.pdf

we present a novel architecture, ZS3Net, combining a deep visual segmentation model with an approach to generate visual representations from semantic word embeddings. By this way, ZS3Net addresses pixel classification tasks where both seen and unseen categories are faced at test time (so called “generalized” zero-shot classification)

