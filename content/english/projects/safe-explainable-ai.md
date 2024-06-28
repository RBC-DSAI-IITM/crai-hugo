---

title: "Safe Transfer learning among different dynamical agents"
image: "images/safe.png"
draft: false
researchers: ["Returaj Burnwal", "Anirban Santara", "Nirav P. Bhatt", "Balaraman Ravindran", "Gaurav Aggarwal"]
filters: [ai-and-society]
tags: ["safe-ai", "reinforcement-learning"]
---

Model predictive control (MPC) is a popular approach for trajectory optimization in practical robotics applications. MPC policies can optimize trajectory parameters under kinodynamic and safety constraints and provide guarantees on safety, optimality, generalizability, interpretability, and explainability. However, some behaviors are complex and it is difficult to hand-craft an MPC objective function. A special class of MPC policies called Learnable-MPC addresses this difficulty using imitation learning from expert demonstrations. However, they require the demonstrator and the imitator agents to be identical which is hard to satisfy in many real world applications of robotics. In this paper, we address the practical problem of training Learnable-MPC policies when the demonstrator and the imitator do not share the same dynamics and their state spaces may have a partial overlap. We propose a novel approach that uses a generative adversarial network (GAN) to minimize the Jensen-Shannon divergence between the state-trajectory distributions of the demonstrator and the imitator. We evaluate our approach on a variety of simulated robotics tasks of DeepMind Control suite and demonstrate the efficacy of our approach at learning the demonstrator's behavior without having to copy their actions. 