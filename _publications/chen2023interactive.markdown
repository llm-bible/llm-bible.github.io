---
layout: publication
title: See Think Confirm Interactive Prompting Between Vision And Language Models For Knowledge45;based Visual Reasoning
authors: Chen Zhenfang, Zhou Qinhong, Shen Yikang, Hong Yining, Zhang Hao, Gan Chuang
conference: "Arxiv"
year: 2023
bibkey: chen2023interactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.05226"}
tags: ['Ethics And Bias', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large pre45;trained vision and language models have demonstrated remarkable capacities for various tasks. However solving the knowledge45;based visual reasoning tasks remains challenging which requires a model to comprehensively understand image content connect the external world knowledge and perform step45;by45;step reasoning to answer the questions correctly. To this end we propose a novel framework named Interactive Prompting Visual Reasoner (IPVR) for few45;shot knowledge45;based visual reasoning. IPVR contains three stages see think and confirm. The see stage scans the image and grounds the visual concept candidates with a visual perception model. The think stage adopts a pre45;trained large language model (LLM) to attend to the key concepts from candidates adaptively. It then transforms them into text context for prompting with a visual captioning model and adopts the LLM to generate the answer. The confirm stage further uses the LLM to generate the supporting rationale to the answer verify the generated rationale with a cross45;modality classifier and ensure that the rationale can infer the predicted output consistently. We conduct experiments on a range of knowledge45;based visual reasoning datasets. We found our IPVR enjoys several benefits 1). it achieves better performance than the previous few45;shot learning baselines; 2). it enjoys the total transparency and trustworthiness of the whole reasoning process by providing rationales for each reasoning step; 3). it is computation45;efficient compared with other fine45;tuning baselines.
