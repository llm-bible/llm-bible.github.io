---
layout: publication
title: Infmllm\: A Unified Framework For Visual-language Tasks
authors: Zhou Qiang, Wang Zhibin, Chu Wei, Xu Yinghui, Li Hao, Qi Yuan
conference: "Arxiv"
year: 2023
bibkey: zhou2023unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06791"}
  - {name: "Code", url: "https://github.com/mightyzau/InfMLLM"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have proven their remarkable versatility in handling a comprehensive range of language-centric applications. To expand LLMs capabilities to a broader spectrum of modal inputs multimodal large language models (MLLMs) have attracted growing interest. This work delves into enabling LLMs to tackle more vision-language-related tasks particularly image captioning visual question answering (VQA) and visual grounding. To this end we implemented a three-stage training scheme starting with lightweight alignment pretraining then moderate-weight multitask hybrid training and finally LLM fine-tuning to improve instruction following capability. Throughout the training process the requirements on GPU memory gradually increase. To effectively manage the number of visual embeddings passed to the LLM while preserving their positional information we introduce a straightforward visual adapter module dubbed pool-adapter. Our experiments demonstrate that preserving the positional information of visual embeddings through the pool-adapter is particularly beneficial for tasks like visual grounding. We name our proposed approach InfMLLM and have evaluated it extensively on various benchmark datasets. Our results demonstrate that InfMLLM achieves either state-of-the-art (SOTA) performance or performance comparable to recent MLLMs. The code and model will be made open-source at (url)https://github.com/mightyzau/InfMLLM\}."
