---
layout: publication
title: Turning Dust Into Gold\: Distilling Complex Reasoning Capabilities From Llms By Leveraging Negative Data
authors: Li Yiwei, Yuan Peiwen, Feng Shaoxiong, Pan Boyuan, Sun Bin, Wang Xinglin, Wang Heda, Li Kan
conference: "Arxiv"
year: 2023
bibkey: li2023turning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12832"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have performed well on various reasoning tasks but their inaccessibility and numerous parameters hinder wide application in practice. One promising way is distilling the reasoning ability from LLMs to small models by the generated chain-of-thought reasoning paths. In some cases however LLMs may produce incorrect reasoning chains especially when facing complex mathematical problems. Previous studies only transfer knowledge from positive samples and drop the synthesized data with wrong answers. In this work we illustrate the merit of negative data and propose a model specialization framework to distill LLMs with negative samples besides positive ones. The framework consists of three progressive steps covering from training to inference stages to absorb knowledge from negative data. We conduct extensive experiments across arithmetic reasoning tasks to demonstrate the role of negative data in distillation from LLM.
