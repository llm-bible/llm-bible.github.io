---
layout: publication
title: Pretrained Hybrids With MAD Skills
authors: Roberts Nicholas, Guo Samuel, Gao Zhiqi, Gnvv Satya Sai Srinath Namburi, Cromp Sonia, Wu Chengjun, Duan Chengyu, Sala Frederic
conference: "Arxiv"
year: 2024
bibkey: roberts2024pretrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00894"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
While Transformers underpin modern large language models (LMs) there is a growing list of alternative architectures with new capabilities promises and tradeoffs. This makes choosing the right LM architecture challenging. Recently45;proposed textit123;hybrid architectures125; seek a best45;of45;all45;worlds approach that reaps the benefits of all architectures. Hybrid design is difficult for two reasons it requires manual expert45;driven search and new hybrids must be trained from scratch. We propose textbf123;Manticore125; a framework that addresses these challenges. Manticore textit123;automates the design of hybrid architectures125; while reusing pretrained models to create textit123;pretrained125; hybrids. Our approach augments ideas from differentiable Neural Architecture Search (NAS) by incorporating simple projectors that translate features between pretrained blocks from different architectures. We then fine45;tune hybrids that combine pretrained models from different architecture families 45;45; such as the GPT series and Mamba 45;45; end45;to45;end. With Manticore we enable LM selection without training multiple models the construction of pretrained hybrids from existing pretrained models and the ability to textit123;program125; pretrained hybrids to have certain capabilities. Manticore hybrids outperform existing manually45;designed hybrids achieve strong performance on Long Range Arena (LRA) tasks and can improve on pretrained transformers and state space models.
