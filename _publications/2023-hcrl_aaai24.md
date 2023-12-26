---
title: "Advancing Ante Hoc Explainable Models through Generative Adversarial Networks"
collection: publications
permalink: /2023-hcrl_aaai24
excerpt: 'The study introduces a concept learning framework, integrating an explanation generator via adversarial training, enhancing model interpretability for visual classification.'
date: 2024-02-28
venue: 'Human-Centric Representation Learning Workshop at AAAI 2024'
# paperurl: 'https://arxiv.org/abs/2309.02429'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract
This paper presents a novel concept learning framework for enhancing model interpretability and performance in visual classification tasks. Our approach appends an unsupervised explanation generator to the primary classifier network and makes use of adversarial training. During training, the explanation module is optimized to extract visual concepts from the classifier's latent representations, while the GAN-based module aims to discriminate images generated from concepts from true images. This joint training scheme enables the model to implicitly align its internally learned concepts with human-interpretable visual properties. Comprehensive experiments demonstrate the robustness of our approach, while producing coherent concept activations. We analyse the learned concepts, showing their semantic concordance with object parts and visual attributes. We also study how perturbations in the adversarial training protocol impact both classification and concept acquisition.
In summary, this work presents a significant step towards building inherently interpretable deep vision models with task-aligned concept representations - a key enabler for developing trustworthy AI for real-world perception tasks.


<!-- <button type="button" class="btn btn-primary btn-sm" onclick=" window.open('https://arxiv.org/abs/2309.02429','_blank')">Paper</button> -->
<button type="button" class="btn btn-primary btn-sm">To be Updated Soon</button>
<!-- ## Citation
```
@article{osborn,
  author    = {Vimal K B, Saketh Bachu, Tanmay Garg, Vineeth N Balasubramanian, Niveditha Lakshmi Narasimhan, Raghavan Konuru},
  title     = {Building a Winning Team: Selecting Source Model Ensembles using a Submodular Transferability Estimation
               Approach},
  journal   = {ICCV},
  year      = {2023},
}
``` -->