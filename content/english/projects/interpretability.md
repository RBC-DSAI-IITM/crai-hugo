---
title: "On the Interpretability of Attention Networks"
image: "/images/blackbox.webp"
pis: "Lakshmi Narayan Pandey, Rahul Vashisht, Harish G. Ramaswamy"
filters: [making-ai-understandable]
draft: false
---

<style>
    .link-button
{
  padding: .6rem 1.2rem;
  line-height: 2.1rem;
  font-size: 1.2rem;
  color: #000;
  border: 2px solid transparent;
  border-radius: .5rem;
  text-decoration: none;
  transition: all .3s ease-in;
  background-color: #4eadec !important;
}
    .link-button .button_text 
    {
        text-decoration: none; 
        color: black; 
    }
</style>

<button class="link-button">
    <a class="button_text" href="https://proceedings.mlr.press/v189/pandey23a.html" target="_blank">View</a>
</button>

<strong>Abstract:</strong>

Attention mechanisms form a core component of several successful deep learning architectures, and are based on one key idea: “The output depends only on a small (but unknown) segment of the input.” In several practical applications like image captioning and language translation, this is mostly true. In trained models with an attention mechanism, the outputs of an intermediate module that encodes the segment of input responsible for the output is often used as a way to peek into the ‘reasoning’ of the network. We make such a notion more precise for a variant of the classification problem that we term selective dependence classification (SDC) when used with attention model architectures. Under such a setting, we demonstrate various error modes where an attention model can be accurate but fail to be interpretable, and show that such models do occur as a result of training. We illustrate various situations that can accentuate and mitigate this behaviour. Finally, we use our objective definition of interpretability for SDC tasks to evaluate a few attention model learning algorithms designed to encourage sparsity and demonstrate that these algorithms help improve interpretability. 