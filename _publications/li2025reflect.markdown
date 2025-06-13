---
layout: publication
title: 'Reflect-dit: Inference-time Scaling For Text-to-image Diffusion Transformers Via In-context Reflection'
authors: Shufan Li, Konstantinos Kallidromitis, Akash Gokul, Arsh Koneru, Yusuke Kato, Kazuki Kozuka, Aditya Grover
conference: "Arxiv"
year: 2025
bibkey: li2025reflect
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.12271'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Merging', 'Prompting', 'Pretraining Methods']
---
The predominant approach to advancing text-to-image generation has been
training-time scaling, where larger models are trained on more data using
greater computational resources. While effective, this approach is
computationally expensive, leading to growing interest in inference-time
scaling to improve performance. Currently, inference-time scaling for
text-to-image diffusion models is largely limited to best-of-N sampling, where
multiple images are generated per prompt and a selection model chooses the best
output. Inspired by the recent success of reasoning models like DeepSeek-R1 in
the language domain, we introduce an alternative to naive best-of-N sampling by
equipping text-to-image Diffusion Transformers with in-context reflection
capabilities. We propose Reflect-DiT, a method that enables Diffusion
Transformers to refine their generations using in-context examples of
previously generated images alongside textual feedback describing necessary
improvements. Instead of passively relying on random sampling and hoping for a
better result in a future generation, Reflect-DiT explicitly tailors its
generations to address specific aspects requiring enhancement. Experimental
results demonstrate that Reflect-DiT improves performance on the GenEval
benchmark (+0.19) using SANA-1.0-1.6B as a base model. Additionally, it
achieves a new state-of-the-art score of 0.81 on GenEval while generating only
20 samples per prompt, surpassing the previous best score of 0.80, which was
obtained using a significantly larger model (SANA-1.5-4.8B) with 2048 samples
under the best-of-N approach.
