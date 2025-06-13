---
layout: publication
title: '[CLS] Token Tells Everything Needed For Training-free Efficient Mllms'
authors: Ao Wang, Fengyuan Sun, Hui Chen, Zijia Lin, Jungong Han, Guiguang Ding
conference: "Arxiv"
year: 2024
bibkey: wang2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05819"}
  - {name: "Code", url: "https://github.com/THU-MIG/VTC-CLS"}
tags: ['Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models', 'Prompting']
---
Multimodal Large Language Models (MLLMs) have recently demonstrated strong
performance across a wide range of vision-language tasks, garnering significant
attention in the computer vision. However, their efficient deployment remains a
substantial challenge due to high computational costs and memory requirements.
Recognizing the redundancy of information within the vision modality, recent
studies have explored methods for compressing visual tokens in MLLMs to enhance
efficiency in a training-free manner. Despite their effectiveness, existing
methods like Fast rely on the attention between visual tokens and prompt text
tokens as the importance indicator, overlooking the relevance to response text
and thus introducing perception bias. In this paper, we demonstrate that in
MLLMs, the [CLS] token in the visual encoder inherently knows which visual
tokens are important for MLLMs. Building on this prior, we introduce a simple
yet effective method for train-free visual token compression, called VTC-CLS.
Firstly, it leverages the attention score of the [CLS] token on visual tokens
as an importance indicator for pruning visual tokens. Besides, we also explore
ensembling the importance scores derived by the [CLS] token from different
layers to capture the key visual information more comprehensively. Extensive
experiments demonstrate that our VTC-CLS achieves the state-of-the-art
performance across various tasks compared with baseline methods. It also brings
notably less computational costs in a training-free manner, highlighting its
effectiveness and superiority. Code and models are available at
\url\{https://github.com/THU-MIG/VTC-CLS\}.
