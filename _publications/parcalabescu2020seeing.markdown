---
layout: publication
title: 'Seeing Past Words: Testing The Cross-modal Capabilities Of Pretrained V&L
  Models On Counting Tasks'
authors: Letitia Parcalabescu, Albert Gatt, Anette Frank, Iacer Calixto
conference: Proceedings of the 1st Workshop on Multimodal Semantic Representations
  (MMSR) 2021 Groningen Netherlands (Online) Association for Computational Linguistics
  p. 32--44
year: 2020
citations: 18
bibkey: parcalabescu2020seeing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.12352'}]
tags: [Ethics and Bias, Interpretability and Explainability, Multimodal Models]
---
We investigate the reasoning ability of pretrained vision and language (V&L)
models in two tasks that require multimodal integration: (1) discriminating a
correct image-sentence pair from an incorrect one, and (2) counting entities in
an image. We evaluate three pretrained V&L models on these tasks: ViLBERT,
ViLBERT 12-in-1 and LXMERT, in zero-shot and finetuned settings. Our results
show that models solve task (1) very well, as expected, since all models are
pretrained on task (1). However, none of the pretrained V&L models is able to
adequately solve task (2), our counting probe, and they cannot generalise to
out-of-distribution quantities. We propose a number of explanations for these
findings: LXMERT (and to some extent ViLBERT 12-in-1) show some evidence of
catastrophic forgetting on task (1). Concerning our results on the counting
probe, we find evidence that all models are impacted by dataset bias, and also
fail to individuate entities in the visual input. While a selling point of
pretrained V&L models is their ability to solve complex tasks, our findings
suggest that understanding their reasoning and grounding capabilities requires
more targeted investigations on specific phenomena.