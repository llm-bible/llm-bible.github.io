---
layout: publication
title: 'Prompt-consistency Image Generation (PCIG): A Unified Framework Integrating Llms, Knowledge Graphs, And Controllable Diffusion Models'
authors: Yichen Sun, Zhixuan Chu, Zhan Qin, Kui Ren
conference: "Arxiv"
year: 2024
bibkey: sun2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16333"}
  - {name: "Code", url: "https://github.com/TruthAI-Lab/PCIG"}
tags: ['Tools', 'Applications', 'RAG', 'Merging', 'Has Code', 'Multimodal Models', 'Prompting']
---
The rapid advancement of Text-to-Image(T2I) generative models has enabled the
synthesis of high-quality images guided by textual descriptions. Despite this
significant progress, these models are often susceptible in generating contents
that contradict the input text, which poses a challenge to their reliability
and practical deployment. To address this problem, we introduce a novel
diffusion-based framework to significantly enhance the alignment of generated
images with their corresponding descriptions, addressing the inconsistency
between visual output and textual input. Our framework is built upon a
comprehensive analysis of inconsistency phenomena, categorizing them based on
their manifestation in the image. Leveraging a state-of-the-art large language
module, we first extract objects and construct a knowledge graph to predict the
locations of these objects in potentially generated images. We then integrate a
state-of-the-art controllable image generation model with a visual text
generation module to generate an image that is consistent with the original
prompt, guided by the predicted object locations. Through extensive experiments
on an advanced multimodal hallucination benchmark, we demonstrate the efficacy
of our approach in accurately generating the images without the inconsistency
with the original prompt. The code can be accessed via
https://github.com/TruthAI-Lab/PCIG.
