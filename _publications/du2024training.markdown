---
layout: publication
title: 'Blenderllm: Training Large Language Models For Computer-aided Design With Self-improvement'
authors: Yuhao Du, Shunian Chen, Wenbo Zan, Peizhao Li, Mingxuan Wang, Dingjie Song, Bo Li, Yan Hu, Benyou Wang
conference: "Arxiv"
year: 2024
bibkey: du2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14203"}
  - {name: "Code", url: "https://github.com/FreedomIntelligence/BlenderLLM"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The application of Large Language Models (LLMs) in Computer-Aided Design
(CAD) remains an underexplored area, despite their remarkable advancements in
other domains. In this paper, we present BlenderLLM, a novel framework for
training LLMs specifically for CAD tasks leveraging a self-improvement
methodology. To support this, we developed a bespoke training dataset,
BlendNet, and introduced a comprehensive evaluation suite, CADBench. Our
results reveal that existing models demonstrate significant limitations in
generating accurate CAD scripts. However, through minimal instruction-based
fine-tuning and iterative self-improvement, BlenderLLM significantly surpasses
these models in both functionality and accuracy of CAD script generation. This
research establishes a strong foundation for the application of LLMs in CAD
while demonstrating the transformative potential of self-improving models in
advancing CAD automation. We encourage further exploration and adoption of
these methodologies to drive innovation in the field. The dataset, model,
benchmark, and source code are publicly available at
https://github.com/FreedomIntelligence/BlenderLLM
