---

title: "Interpretability with Accurate Small Models"
image: "https://www.frontiersin.org/files/Articles/507097/frai-03-00003-HTML/image_m/frai-03-00003-g001.jpg"
draft: false
researchers: ["Abhishek Ghose, Balaraman Ravindran"]
filters: [making-ai-understandable]
reslinks: ["https://arxiv.org/abs/1905.01520"]
tags: ["making-ai-understandable"]
reslinktitles: ["Interpretability with Accurate Small Models: arxiv.org"]
---

Models often need to be constrained to a certain size for them to be considered interpretable. For example, a decision tree of depth 5 is much easier to understand than one of depth 50. Limiting model size, however, often reduces accuracy. We suggest a practical technique that minimizes this trade-off between interpretability and classification accuracy. This enables an arbitrary learning algorithm to produce highly accurate small-sized models. Our technique identifies the training data distribution to learn from that leads to the highest accuracy for a model of a given size.

We represent the training distribution as a combination of sampling schemes. Each scheme is defined by a parameterized probability mass function applied to the segmentation produced by a decision tree. An Infinite Mixture Model with Beta components is used to represent a combination of such schemes. The mixture model parameters are learned using Bayesian Optimization. Under simplistic assumptions, we would need to optimize for O(d) variables for a distribution over a d-dimensional input space, which is cumbersome for most real-world data. However, we show that our technique significantly reduces this number to a \emph{fixed set of eight variables} at the cost of relatively cheap preprocessing. The proposed technique is flexible: it is \emph{model-agnostic}, i.e., it may be applied to the learning algorithm for any model family, and it admits a general notion of model size. We demonstrate its effectiveness using multiple real-world datasets to construct decision trees, linear probability models and gradient boosted models with different sizes. We observe significant improvements in the F1-score in most instances, exceeding an improvement of 100% in some cases. 