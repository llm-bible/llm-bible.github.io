---
layout: publication
title: 'Object-level Visual Prompts For Compositional Image Generation'
authors: Gaurav Parmar, Or Patashnik, Kuan-chieh Wang, Daniil Ostashev, Srinivasa Narasimhan, Jun-yan Zhu, Daniel Cohen-or, Kfir Aberman
conference: "Arxiv"
year: 2025
bibkey: parmar2025object
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01424"}
tags: ['Model Architecture', 'Merging', 'Reinforcement Learning', 'Attention Mechanism', 'Prompting']
---
We introduce a method for composing object-level visual prompts within a
text-to-image diffusion model. Our approach addresses the task of generating
semantically coherent compositions across diverse scenes and styles, similar to
the versatility and expressiveness offered by text prompts. A key challenge in
this task is to preserve the identity of the objects depicted in the input
visual prompts, while also generating diverse compositions across different
images. To address this challenge, we introduce a new KV-mixed cross-attention
mechanism, in which keys and values are learned from distinct visual
representations. The keys are derived from an encoder with a small bottleneck
for layout control, whereas the values come from a larger bottleneck encoder
that captures fine-grained appearance details. By mixing keys and values from
these complementary sources, our model preserves the identity of the visual
prompts while supporting flexible variations in object arrangement, pose, and
composition. During inference, we further propose object-level compositional
guidance to improve the method's identity preservation and layout correctness.
Results show that our technique produces diverse scene compositions that
preserve the unique characteristics of each visual prompt, expanding the
creative potential of text-to-image generation.
