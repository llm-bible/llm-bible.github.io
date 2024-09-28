---
layout: publication
title: Augmenting Interpretable Models with LLMs during Training
authors: Singh Chandan, Askari Armin, Caruana Rich, Gao Jianfeng
conference: "Nature Communications"
year: 2022
bibkey: singh2022augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.11799"}
tags: ['Efficiency And Optimization', 'GPT', 'Interpretability', 'Interpretability And Interpretability', 'LLM', 'RAG', 'Tools']
---
Recent large language models (LLMs) have demonstrated remarkable prediction performance for a growing array of tasks. However their proliferation into high-stakes domains (e.g. medicine) and compute-limited settings has created a burgeoning need for interpretability and efficiency. We address this need by proposing Augmented Interpretable Models (Aug-imodels) a framework for leveraging the knowledge learned by LLMs to build extremely efficient and interpretable models. Aug-imodels use LLMs during fitting but not during inference allowing complete transparency and often a speed/memory improvement of greater than 1000x for inference compared to LLMs. We explore two instantiations of Aug-imodels in natural-language processing (i) Aug-GAM which augments a generalized additive model with decoupled embeddings from an LLM and (ii) Aug-Tree which augments a decision tree with LLM feature expansions. Across a variety of text-classification datasets both outperform their non-augmented counterparts. Aug-GAM can even outperform much larger models (e.g. a 6-billion parameter GPT-J model) despite having 10000x fewer parameters and being fully transparent. We further explore Aug-imodels in a natural-language fMRI study where they generate interesting interpretations from scientific data. All code for using Aug-imodels and reproducing results is made available on Github.
