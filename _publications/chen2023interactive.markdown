---
layout: publication
title: See, Think, Confirm: Interactive Prompting Between Vision And Language Models For Knowledge-based Visual Reasoning
authors: Chen Zhenfang, Zhou Qinhong, Shen Yikang, Hong Yining, Zhang Hao, Gan Chuang
conference: "Arxiv"
year: 2023
bibkey: chen2023interactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.05226"}
tags: ['Ethics And Bias', 'Few Shot', 'Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large pre-trained vision and language models have demonstrated remarkable capacities for various tasks. However solving the knowledge-based visual reasoning tasks remains challenging which requires a model to comprehensively understand image content connect the external world knowledge and perform step-by-step reasoning to answer the questions correctly. To this end we propose a novel framework named Interactive Prompting Visual Reasoner (IPVR) for few-shot knowledge-based visual reasoning. IPVR contains three stages see think and confirm. The see stage scans the image and grounds the visual concept candidates with a visual perception model. The think stage adopts a pre-trained large language model (LLM) to attend to the key concepts from candidates adaptively. It then transforms them into text context for prompting with a visual captioning model and adopts the LLM to generate the answer. The confirm stage further uses the LLM to generate the supporting rationale to the answer verify the generated rationale with a cross-modality classifier and ensure that the rationale can infer the predicted output consistently. We conduct experiments on a range of knowledge-based visual reasoning datasets. We found our IPVR enjoys several benefits 1). it achieves better performance than the previous few-shot learning baselines; 2). it enjoys the total transparency and trustworthiness of the whole reasoning process by providing rationales for each reasoning step; 3). it is computation-efficient compared with other fine-tuning baselines.
