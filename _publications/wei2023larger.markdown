---
layout: publication
title: Larger Language Models Do In45;context Learning Differently
authors: Wei Jerry, Wei Jason, Tay Yi, Tran Dustin, Webson Albert, Lu Yifeng, Chen Xinyun, Liu Hanxiao, Huang Da, Zhou Denny, Ma Tengyu
conference: "Arxiv"
year: 2023
bibkey: wei2023larger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.03846"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We study how in45;context learning (ICL) in language models is affected by semantic priors versus input45;label mappings. We investigate two setups45;ICL with flipped labels and ICL with semantically45;unrelated labels45;across various model families (GPT45;3 InstructGPT Codex PaLM and Flan45;PaLM). First experiments on ICL with flipped labels show that overriding semantic priors is an emergent ability of model scale. While small language models ignore flipped labels presented in45;context and thus rely primarily on semantic priors from pretraining large models can override semantic priors when presented with in45;context exemplars that contradict priors despite the stronger semantic priors that larger models may hold. We next study semantically45;unrelated label ICL (SUL45;ICL) in which labels are semantically unrelated to their inputs (e.g. foo/bar instead of negative/positive) thereby forcing language models to learn the input45;label mappings shown in in45;context exemplars in order to perform the task. The ability to do SUL45;ICL also emerges primarily with scale and large45;enough language models can even perform linear classification in a SUL45;ICL setting. Finally we evaluate instruction45;tuned models and find that instruction tuning strengthens both the use of semantic priors and the capacity to learn input45;label mappings but more of the former.
