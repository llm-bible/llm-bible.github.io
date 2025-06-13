---
layout: publication
title: 'On Multi-token Prediction For Efficient LLM Inference'
authors: Somesh Mehra, Javier Alonso Garcia, Lukas Mauch
conference: "Arxiv"
year: 2025
bibkey: mehra2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09419"}
tags: ['Prompting', 'Training Techniques']
---
We systematically investigate multi-token prediction (MTP) capabilities
within LLMs pre-trained for next-token prediction (NTP). We first show that
such models inherently possess MTP capabilities via numerical marginalization
over intermediate token probabilities, though performance is data-dependent and
improves with model scale. Furthermore, we explore the challenges of
integrating MTP heads into frozen LLMs and find that their hidden layers are
strongly specialized for NTP, making adaptation non-trivial. Finally, we show
that while joint training of MTP heads with the backbone improves performance,
it cannot fully overcome this barrier, prompting further research in this
direction. Our findings provide a deeper understanding of MTP applied to
pretrained LLMs, informing strategies for accelerating inference through
parallel token prediction.
