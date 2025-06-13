---
layout: publication
title: 'PLANNER: Generating Diversified Paragraph Via Latent Language Diffusion Model'
authors: Yizhe Zhang, Jiatao Gu, Zhuofeng Wu, Shuangfei Zhai, Josh Susskind, Navdeep Jaitly
conference: "Arxiv"
year: 2023
bibkey: zhang2023generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02531"}
tags: ['Language Modeling', 'Merging', 'GPT', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Applications']
---
Autoregressive models for text sometimes generate repetitive and low-quality
output because errors accumulate during the steps of generation. This issue is
often attributed to exposure bias - the difference between how a model is
trained, and how it is used during inference. Denoising diffusion models
provide an alternative approach in which a model can revisit and revise its
output. However, they can be computationally expensive and prior efforts on
text have led to models that produce less fluent output compared to
autoregressive models, especially for longer text and paragraphs. In this
paper, we propose PLANNER, a model that combines latent semantic diffusion with
autoregressive generation, to generate fluent text while exercising global
control over paragraphs. The model achieves this by combining an autoregressive
"decoding" module with a "planning" module that uses latent diffusion to
generate semantic paragraph embeddings in a coarse-to-fine manner. The proposed
method is evaluated on various conditional generation tasks, and results on
semantic generation, text completion and summarization show its effectiveness
in generating high-quality long-form text in an efficient manner.
