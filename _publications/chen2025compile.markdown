---
layout: publication
title: 'Compile Scene Graphs With Reinforcement Learning'
authors: Zuyao Chen, Jinlin Wu, Zhen Lei, Marc Pollefeys, Chang Wen Chen
conference: "Arxiv"
year: 2025
bibkey: chen2025compile
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13617"}
  - {name: "Code", url: "https://github.com/gpt4vision/R1-SGG"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
Next-token prediction is the fundamental principle for training large language models (LLMs), and reinforcement learning (RL) further enhances their reasoning performance. As an effective way to model language, image, video, and other modalities, the use of LLMs for end-to-end extraction of structured visual representations, such as scene graphs, remains underexplored. It requires the model to accurately produce a set of objects and relationship triplets, rather than generating text token by token. To achieve this, we introduce R1-SGG, a multimodal LLM (M-LLM) initially trained via supervised fine-tuning (SFT) on the scene graph dataset and subsequently refined using reinforcement learning to enhance its ability to generate scene graphs in an end-to-end manner. The SFT follows a conventional prompt-response paradigm, while RL requires the design of effective reward signals. We design a set of graph-centric rewards, including three recall-based variants -- Hard Recall, Hard Recall+Relax, and Soft Recall -- which evaluate semantic and spatial alignment between predictions and ground truth at the object and relation levels. A format consistency reward further ensures that outputs follow the expected structural schema. Extensive experiments on the VG150 and PSG benchmarks show that R1-SGG substantially reduces failure rates and achieves strong performance in Recall and mean Recall, surpassing traditional SGG models and existing multimodal language models. Our code is available at https://github.com/gpt4vision/R1-SGG
