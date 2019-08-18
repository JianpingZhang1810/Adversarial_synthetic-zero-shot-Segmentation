# Adversarial_synthetic-zero-shot-Segmentation

## Adversarial datasugmentation in semantic segmentation

## Synthetic dataset for semantic segmentation
### 1 Learning Semantic Segmentation from Synthetic Data: A Geometrically Guided Input-Output Adaptation Approach
https://arxiv.org/pdf/1812.05040.pdf

we take the advantage of additional geometric information from synthetic data, a powerful yet largely neglected cue, to bridge the domain gap. Such geometric information can be generated easily from synthetic data and is proven to be closely coupled with semantic information. With the geometric information, we propose a model to reduce domain shift on two levels: on the input level, we augment the traditional image translation network with the additional geometric information to translate synthetic images into realistic styles; on the output level, we build a task network which simultaneously performs depth estimation and semantic segmentation on the synthetic data. Meanwhile, we encourage the network to preserve the correlation between depth and semantics by adversarial training on the output space.
### 2 Playing for Data: Ground Truth from Computer Games
https://arxiv.org/pdf/1608.02192.pdf
we present an approach to rapidly creating pixel-accurate semantic label maps for images extracted from modern computer games. Although the source code and the internal operation of commercial games are inaccessible, we show that associations between image patches can be reconstructed from the communication between the game and the graphics hardware. This enables rapid propagation of semantic labels within and across images synthesized by the game, with no access to the source code or the content


## Zero-shot semantic segmentation
### 1 Zero-Shot Semantic Segmentation
https://arxiv.org/pdf/1906.00817.pdf

we present a novel architecture, ZS3Net, combining a deep visual segmentation model with an approach to generate visual representations from semantic word embeddings. By this way, ZS3Net addresses pixel classification tasks where both seen and unseen categories are faced at test time (so called “generalized” zero-shot classification)

