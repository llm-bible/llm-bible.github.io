---
layout: publication
title: Augmenting Interpretable Models With Llms During Training
authors: Singh Chandan, Askari Armin, Caruana Rich, Gao Jianfeng
conference: "Nature Communications"
year: 2022
bibkey: singh2022augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.11799"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Recent large language models (LLMs) have demonstrated remarkable prediction performance for a growing array of tasks. However their proliferation into high45;stakes domains (e.g. medicine) and compute45;limited settings has created a burgeoning need for interpretability and efficiency. We address this need by proposing Augmented Interpretable Models (Aug45;imodels) a framework for leveraging the knowledge learned by LLMs to build extremely efficient and interpretable models. Aug45;imodels use LLMs during fitting but not during inference allowing complete transparency and often a speed/memory improvement of greater than 1000x for inference compared to LLMs. We explore two instantiations of Aug45;imodels in natural45;language processing (i) Aug45;GAM which augments a generalized additive model with decoupled embeddings from an LLM and (ii) Aug45;Tree which augments a decision tree with LLM feature expansions. Across a variety of text45;classification datasets both outperform their non45;augmented counterparts. Aug45;GAM can even outperform much larger models (e.g. a 645;billion parameter GPT45;J model) despite having 10000x fewer parameters and being fully transparent. We further explore Aug45;imodels in a natural45;language fMRI study where they generate interesting interpretations from scientific data. All code for using Aug45;imodels and reproducing results is made available on Github.
