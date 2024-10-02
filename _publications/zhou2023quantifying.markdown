---
layout: publication
title: 'Quantifying And Analyzing Entity-level Memorization In Large Language Models'
authors: Zhou Zhenhong, Xiang Jiuyang, Chen Chaomeng, Su Sen
conference: "Arxiv"
year: 2023
bibkey: zhou2023quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15727"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have been proven capable of memorizing their training data, which can be extracted through specifically designed prompts. As the scale of datasets continues to grow, privacy risks arising from memorization have attracted increasing attention. Quantifying language model memorization helps evaluate potential privacy risks. However, prior works on quantifying memorization require access to the precise original data or incur substantial computational overhead, making it difficult for applications in real-world language models. To this end, we propose a fine-grained, entity-level definition to quantify memorization with conditions and metrics closer to real-world scenarios. In addition, we also present an approach for efficiently extracting sensitive entities from autoregressive language models. We conduct extensive experiments based on the proposed, probing language models' ability to reconstruct sensitive entities under different settings. We find that language models have strong memorization at the entity level and are able to reproduce the training data even with partial leakages. The results demonstrate that LLMs not only memorize their training data but also understand associations between entities. These findings necessitate that trainers of LLMs exercise greater prudence regarding model memorization, adopting memorization mitigation techniques to preclude privacy violations.
