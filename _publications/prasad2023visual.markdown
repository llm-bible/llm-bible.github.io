---
layout: publication
title: Rephrase, Augment, Reason\: Visual Grounding Of Questions For Vision-language Models
authors: Prasad Archiki, Stengel-eskin Elias, Bansal Mohit
conference: "Arxiv"
year: 2023
bibkey: prasad2023visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05861"}
tags: ['Applications', 'Few Shot', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
An increasing number of vision-language tasks can be handled with little to no training i.e. in a zero and few-shot manner by marrying large language models (LLMs) to vision encoders resulting in large vision-language models (LVLMs). While this has huge upsides such as not requiring training data or custom architectures how an input is presented to an LVLM can have a major impact on zero-shot model performance. In particular inputs phrased in an underspecified way can result in incorrect answers due to factors like missing visual information complex implicit reasoning or linguistic ambiguity. Therefore adding visually-grounded information to the input as a preemptive clarification should improve model performance by reducing underspecification e.g. by localizing objects and disambiguating references. Similarly in the VQA setting changing the way questions are framed can make them easier for models to answer. To this end we present Rephrase Augment and Reason (RepARe) a gradient-free framework that extracts salient details about the image using the underlying LVLM as a captioner and reasoner in order to propose modifications to the original question. We then use the LVLMs confidence over a generated answer as an unsupervised scoring function to select the rephrased question most likely to improve zero-shot performance. Focusing on three visual question answering tasks we show that RepARe can result in a 3.8537; (absolute) increase in zero-shot accuracy on VQAv2 6.4137; and 7.9437; points increase on A-OKVQA and VizWiz respectively. Additionally we find that using gold answers for oracle question candidate selection achieves a substantial gain in VQA accuracy by up to 14.4137;. Through extensive analysis we demonstrate that outputs from RepARe increase syntactic complexity and effectively utilize vision-language interaction and the frozen LLM.
