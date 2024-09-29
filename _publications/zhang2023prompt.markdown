---
layout: publication
title: Prompt Highlighter Interactive Control For Multi45;modal Llms
authors: Yuechen Zhang, Shengju Qian, Bohao Peng, Shu Liu, Jiaya Jia
conference: "Arxiv"
year: 2023
bibkey: zhang2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2312.04302v2"}
  - {name: "Code", url: "https://github.com/dvlab&#45;research/Prompt&#45;Highlighter/"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques']
---
This study targets a critical aspect of multi45;modal LLMs (LLMsamp;VLMs) inference explicit controllable text generation. Multi45;modal LLMs empower multi45;modality understanding with the capability of semantic generation yet bring less explainability and heavier reliance on prompt contents due to their autoregressive generative nature. While manipulating prompt formats could improve outputs designing specific and precise prompts per task can be challenging and ineffective. To tackle this issue we introduce a novel inference method Prompt Highlighter which enables users to highlight specific prompt spans to interactively control the focus during generation. Motivated by the classifier45;free diffusion guidance we form regular and unconditional context pairs based on highlighted tokens demonstrating that the autoregressive generation in models can be guided in a classifier45;free way. Notably we find that during inference guiding the models with highlighted tokens through the attention weights leads to more desired outputs. Our approach is compatible with current LLMs and VLMs achieving impressive customized generation results without training. Experiments confirm its effectiveness in focusing on input contexts and generating reliable content. Without tuning on LLaVA45;v1.5 our method secured 70.7 in the MMBench test and 1552.5 in MME45;perception. The code is available at https://github.com/dvlab&#45;research/Prompt&#45;Highlighter/
