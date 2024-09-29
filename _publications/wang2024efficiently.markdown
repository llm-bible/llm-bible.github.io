---
layout: publication
title: Modaverse&#58; Efficiently Transforming Modalities With Llms
authors: Wang Xinyu, Zhuang Bohan, Wu Qi
conference: "Arxiv"
year: 2024
bibkey: wang2024efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06395"}
tags: ['Agentic', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Humans possess the capability to comprehend diverse modalities and seamlessly transfer information between them. In this work we introduce ModaVerse a Multi-modal Large Language Model (MLLM) capable of comprehending and transforming content across various modalities including images videos and audio. Predominant MLLM frameworks have largely relied on the alignment of latent spaces of textual and non-textual features. This alignment process which synchronizes a language model trained on textual data with encoders and decoders trained on multi-modal data often necessitates extensive training of several projection layers in multiple stages. Inspired by LLM-as-agent methodologies we propose a novel Input/Output (I/O) alignment mechanism that operates directly at the level of natural language. It aligns the LLMs output with the input of generative models avoiding the complexities associated with latent feature alignments and simplifying the multiple training stages of existing MLLMs into a single efficient process. This conceptual advancement leads to significant reductions in both data and computational costs. By conducting experiments on several benchmarks we demonstrate that our approach attains comparable performance with the state of the art while achieving considerable efficiencies in data usage and training duration.
