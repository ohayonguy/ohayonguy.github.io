---
title: "The Perception-Robustness Tradeoff in Deterministic Image Restoration" 
#date: 2024-05-22
tags: ["image restoration","robustness","stability","image processing","computer vision"]
author: ["Guy Ohayon, Tomer Michaeli, Michael Elad"]
description: "We prove that there is a fundamental tradeoff between the perceptual quality and the stability of image restoration algorithms." 
summary: "We prove that there is a fundamental tradeoff between the perceptual quality and the stability of image restoration algorithms." 
cover:
    image: "paper1.png"
    alt: "Qualitative illustration of the discovered tradeoff."
    relative: false
#editPost:
 #   URL: "https://doi.org/10.1073/pnas.1816454115"
 #   Text: "Other Journal Name"

---

##### Abstract

We study the behavior of deterministic methods for solving inverse problems in imaging. These methods are commonly designed to achieve two goals: (1) attaining high perceptual quality, and (2) generating reconstructions that are consistent with the measurements. We provide a rigorous proof that the better a predictor satisfies these two requirements, the larger its Lipschitz constant must be, regardless of the nature of the degradation involved. In particular, to approach perfect perceptual quality and perfect consistency, the Lipschitz constant of the model must grow to infinity. This implies that such methods are necessarily more susceptible to adversarial attacks. We demonstrate our theory on single image super-resolution algorithms, addressing both noisy and noiseless settings. We also show how this undesired behavior can be leveraged to explore the posterior distribution, thereby allowing the deterministic model to imitate stochastic methods.

---

##### Download

+ [You can find the paper here.](https://proceedings.mlr.press/v235/ohayon24a.html)
+ This paper was a spotlight poster at ICML 2024 (3.5% acceptance rate).
<!-- + [Online appendix](appendix2.pdf)
+ [Code and data](https://github.com/pmichaillat/unemployment-gap) -->

---

##### Qualitative illustration of the proposed notion of perceptual fairness

![](paper1.png)

---

##### Citation

```BibTeX

@InProceedings{pmlr-v235-ohayon24a,
  title = 	 {The Perception-Robustness Tradeoff in Deterministic Image Restoration},
  author =       {Ohayon, Guy and Michaeli, Tomer and Elad, Michael},
  booktitle = 	 {Proceedings of the 41st International Conference on Machine Learning},
  pages = 	 {38599--38638},
  year = 	 {2024},
  editor = 	 {Salakhutdinov, Ruslan and Kolter, Zico and Heller, Katherine and Weller, Adrian and Oliver, Nuria and Scarlett, Jonathan and Berkenkamp, Felix},
  volume = 	 {235},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {21--27 Jul},
  publisher =    {PMLR},
  pdf = 	 {https://raw.githubusercontent.com/mlresearch/v235/main/assets/ohayon24a/ohayon24a.pdf},
  url = 	 {https://proceedings.mlr.press/v235/ohayon24a.html}
}

```

---
<!--
##### Related material

+ [Presentation slides](presentation2.pdf)
 -->
