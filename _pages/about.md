---
layout: page
title: About Me
permalink: /about/
description:
nav: true
nav_order: 2
---

<div class="container-fluid">

In these exciting times, self-driving cars are taxis, robots are chefs, and large-language models assist coders, lawyers, and medical professionals alike. This is possible because of amazing progress in large-scale deep neural networks. However, today's large networks have known limitations [1,2,3,4]. Training with GPUs is expensive and meaningfully contributes to climate change [4], our responsibility to ensure data privacy restricts access to important data sources, the interpretability of deep features is lacking [2], and deep networks learn superficially [1]. Perhaps the most pressing outcome from these problems are unpredictable failures and untrustworthy results [1,2,3]. These issues inspire analogies between large-scale deep neural networks and fictional creatures such as *Mistwraiths* and Shoggoth. Mistwraiths use bones of other creatures to construct their own skeleton. They do not care if there are three skulls instead of one, how many arms they have, nor if there is a hand among their feet. All that matters is that they "usually work". However, this concept of "usually working" is limited by the extent of our testing, which is problematic for real-world settings where uncommon events for an individual are often common across a population. In addition, the plethora of research in machine learning and lack of widespread, real-world deployment suggests the gap between "usually working" and "reliably working" is significant. So what can we do to reliably use the power of deep neural networks?

<div class="row">
  <div class="col-sm-5">
    <img class="image-container" src="/assets/img/monster_speech.png" alt="">
  </div>
  <div class="col-sm-2"></div>
  <div class="col-sm-5">
    <img class="image-container" src="/assets/img/human.png" alt="">
  </div>
</div>

*Inductive bias* is one approach to build reliable deep neural networks. In this context, inductive bias is the process of using human knowledge to improve the quality of a deep network on testing data by biasing the network's behavior. To extend our Mistwraith analogy, designing networks with good inductive biases "forces the Mistwraith to read". Incorporating inductive bias into a network is related to architecture design, but extends beyond a specific benchmark or application. An excellent example of inductive bias is **Geometric Deep Learning** [5,6], which aims to improve representation learning by using known regularities of the physical world. An example of a geometric deep learning module is rotationally equivariant convolution [7]  (see also steerable convolution [8]).


<div class="d-flex align-items-center">
  <div class="col-sm-4">
    <img src="/assets/img/spix_purdue.png" width="100%" alt="">
  </div>
  <div class="col-sm-8">
  *Self-similarity* and *superpixels* act as the inductive bias in my research. My current focus is using superpixels to improve the quality of network modules for computer vision. I found modeling images with latent superpixel probabilities can be used to derive an optimal denoiser. This optimal denoiser extends existing attention modules, and leads to significantly better image denoising quality. I have extended this idea to other superpixel-based operators (such as superpixel convolution), which also shows promising results. I am actively studying space-time superpixels, which I believe is important for the 3D understanding of a 2D image. Generally, I believe the best methods for videos will utilize 3D scene understanding. In the future, I will investigate the use of latent 3D scene information to improve networks for 2D videos.
  <p></p>
  </div>
</div>

<div class="d-flex align-items-center">
  <div class="col-sm-4">
    <img src="/assets/img/jetson.png" height=200 alt="">
  </div>
  <div class="col-sm-8">
  My purpose for studying computer vision is to serve as a sensor for automous systems. I love the idea of AI acting in the physical world, and I find it exciting we live in a world where self-driving cars exist. I would love to work on the algorithms for the feasible and safe commercialization of a home robot in the truest Jetson form. The kitchen robot is an example of one such project. These projects will take many decades of focused research across many disciplines, and I believe a core aspect of the solution will be specialized deep neural network modules using inductive bias.
  <p></p>
  </div>
</div>


</div>

Currently, I live in West Lafayette, Indiana, USA. I was raised in Indianapolis, Indiana. I am the youngest of three kids. My sister and brother live in Chicago, Illinois. My parents still live in my childhood home back in Indianapolis. Mohana, Captain America, and Frozen are great movies. I enjoy running long distances when I am not injured. I enjoy reading and coding. I love how people are using machine learning to be creative, with one example being [CMLR](https://github.com/Spijkervet/CLMR).


References
---

1. Wu, Carole-Jean, et al. “Sustainable ai: Environmental implications, challenges and opportunities.” Proceedings of Machine Learning and Systems 4 (2022): 795-813.

2. Bommasani, Rishi, et al. “On the opportunities and risks of foundation models.” arXiv preprint arXiv:2108.07258 (2021).

3. Geirhos, Robert, et al. “Shortcut learning in deep neural networks.” Nature Machine Intelligence 2.11 (2020): 665-673.

4. Dziri, Nouha, et al. “Faith and fate: Limits of transformers on compositionality.” Advances in Neural Information Processing Systems 36 (2024).

5. Bronstein, Michael M., et al. “Geometric deep learning: Grids, groups, graphs, geodesics, and gauges.” arXiv preprint arXiv:2104.13478 (2021).

6. E. Bekkers, An introduction to group equivariant deep learning. Available online: https:uvagedl.github.io

7. Cohen, Taco S., and Max Welling. “Steerable CNNs.” International Conference on Learning Representations. 2022.

8. Freeman, William T., and Edward H. Adelson. “The design and use of steerable filters.” IEEE Transactions on Pattern analysis and machine intelligence 13.9 (1991): 891-906.

9. Ren, and Malik. “Learning a classification model for segmentation.” Proceedings ninth IEEE international conference on computer vision. IEEE, 2003.
