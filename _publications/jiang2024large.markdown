---
layout: publication
title: Large Visual-language Models Are Also Good Classifiers\: A Study Of In-context Multimodal Fake News Detection
authors: Jiang Ye, Wang Yimin
conference: "Arxiv"
year: 2024
bibkey: jiang2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12879"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Large visual-language models (LVLMs) exhibit exceptional performance in visual-language reasoning across diverse cross-modal benchmarks. Despite these advances recent research indicates that Large Language Models (LLMs) like GPT-3.5-turbo underachieve compared to well-trained smaller models such as BERT in Fake News Detection (FND) prompting inquiries into LVLMs efficacy in FND tasks. Although performance could improve through fine-tuning LVLMs the substantial parameters and requisite pre-trained weights render it a resource-heavy endeavor for FND applications. This paper initially assesses the FND capabilities of two notable LVLMs CogVLM and GPT4V in comparison to a smaller yet adeptly trained CLIP model in a zero-shot context. The findings demonstrate that LVLMs can attain performance competitive with that of the smaller model. Next we integrate standard in-context learning (ICL) with LVLMs noting improvements in FND performance though limited in scope and consistency. To address this we introduce the (textbfI)n-context (textbfM)ultimodal (textbfF)ake (textbfN)ews (textbfD)etection (IMFND) framework enriching in-context examples and test inputs with predictions and corresponding probabilities from a well-trained smaller model. This strategic integration directs the LVLMs focus towards news segments associated with higher probabilities thereby improving their analytical accuracy. The experimental results suggest that the IMFND framework significantly boosts the FND efficiency of LVLMs achieving enhanced accuracy over the standard ICL approach across three publicly available FND datasets.
