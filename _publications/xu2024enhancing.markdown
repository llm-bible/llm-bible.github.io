---
layout: publication
title: 'Enhancing Character-level Understanding In Llms Through Token Internal Structure Learning'
authors: Zhu Xu, Zhiqiang Zhao, Zihan Zhang, Yuchi Liu, Quanwei Shen, Fei Liu, Yu Kuang, Jian He, Conglin Liu
conference: "Arxiv"
year: 2024
bibkey: xu2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17679"}
tags: ['Tokenization', 'Efficiency and Optimization', 'Training Techniques']
---
Tokenization methods like Byte-Pair Encoding (BPE) enhance computational efficiency in large language models (LLMs) but often obscure internal character structures within tokens. This limitation hinders LLMs' ability to predict precise character positions, which is crucial in tasks like Chinese Spelling Correction (CSC) where identifying the positions of misspelled characters accelerates correction processes. We propose Token Internal Position Awareness (TIPA), a method that significantly improves models' ability to capture character positions within tokens by training them on reverse character prediction tasks using the tokenizer's vocabulary. Experiments demonstrate that TIPA enhances position prediction accuracy in LLMs, enabling more precise identification of target characters in original text. Furthermore, when applied to downstream tasks that do not require exact position prediction, TIPA still boosts performance in tasks needing character-level information, validating its versatility and effectiveness.
