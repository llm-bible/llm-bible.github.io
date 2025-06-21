---
layout: publication
title: 'BLT: Bidirectional Layout Transformer For Controllable Layout Generation'
authors: Xiang Kong et al.
conference: Arxiv
year: 2021
citations: 26
bibkey: kong2021bidirectional
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.05112'}, {name: Code,
    url: 'https://shawnkx.github.io/blt'}]
tags: [Transformer, Has Code, Model Architecture]
---
Creating visual layouts is a critical step in graphic design. Automatic
generation of such layouts is essential for scalable and diverse visual
designs. To advance conditional layout generation, we introduce BLT, a
bidirectional layout transformer. BLT differs from previous work on
transformers in adopting non-autoregressive transformers. In training, BLT
learns to predict the masked attributes by attending to surrounding attributes
in two directions. During inference, BLT first generates a draft layout from
the input and then iteratively refines it into a high-quality layout by masking
out low-confident attributes. The masks generated in both training and
inference are controlled by a new hierarchical sampling policy. We verify the
proposed model on six benchmarks of diverse design tasks. Experimental results
demonstrate two benefits compared to the state-of-the-art layout transformer
models. First, our model empowers layout transformers to fulfill controllable
layout generation. Second, it achieves up to 10x speedup in generating a layout
at inference time than the layout transformer baseline. Code is released at
https://shawnkx.github.io/blt.