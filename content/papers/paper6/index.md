---
title: "Perceptual Fairness in Image Restoration (NeurIPS 2024)" 
date: 2024-05-22
lastmod: 2024-05-22
tags: [""]
author: ["Guy Ohaayon", "Michael Elad", "Tomer Michaeli"]
description: "We propose a new definition of fairness for image restoration algorithms, draw its connection to previous ones, study its theoretical properties, and demonstrate its practical utility." 
summary: "We propose a new definition of fairness for image restoration algorithms, draw its connection to previous ones, study its theoretical properties, and demonstrate its practical utility." 
cover:
    image: "teaser.png"
    alt: "Illustration of our proposed notion of perceptual fairness."
    relative: false
editPost:
    URL: "https://arxiv.org/pdf/2405.13805"
    Text: "NeurIPS 2024"

---

---

##### Download

+ [Paper](perceptual_fairness.pdf)

---

##### Abstract

Fairness in image restoration tasks is the desire to treat different sub-groups of images equally well. Existing definitions of fairness in image restoration are highly restrictive. They consider a reconstruction to be a correct outcome for a group (e.g., women) only if it falls within the group's set of ground truth images (e.g., natural images of women); otherwise, it is considered entirely incorrect. Consequently, such definitions are prone to controversy, as errors in image restoration can manifest in various ways. In this work we offer an alternative approach towards fairness in image restoration, by considering the Group Perceptual Index (GPI), which we define as the statistical distance between the distribution of the group's ground truth images and the distribution of their reconstructions. We assess the fairness of an algorithm by comparing the GPI of different groups, and say that it achieves perfect Perceptual Fairness (PF) if the GPIs of all groups are identical. We motivate and theoretically study our new notion of fairness, draw its connection to previous ones, and demonstrate its utility on state-of-the-art face image super-resolution algorithms.

---

##### Illustration of our proposed notion of perceptual fairness

![](teaser.png)

---

##### Citation

```BibTeX
@inproceedings{
ohayon2024perceptual,
title={Perceptual Fairness in Image Restoration},
author={Guy Ohayon and Michael Elad and Tomer Michaeli},
booktitle={The Thirty-eighth Annual Conference on Neural Information Processing Systems},
year={2024},
url={https://openreview.net/forum?id=M2QREVHK1V}
}
```