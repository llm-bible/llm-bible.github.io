---
layout: publication
title: KCTS Knowledge45;constrained Tree Search Decoding With Token45;level Hallucination Detection
authors: Choi Sehyun, Fang Tianqing, Wang Zhaowei, Song Yangqiu
conference: "Arxiv"
year: 2023
bibkey: choi2023knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09044"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable human45;level natural language generation capabilities. However their potential to generate misinformation often called the hallucination problem poses a significant risk to their deployment. A common approach to address this issue is to retrieve relevant knowledge and fine45;tune the LLM with the knowledge in its input. Unfortunately this method incurs high training costs and may cause catastrophic forgetting for multi45;tasking models. To overcome these limitations we propose a knowledge45;constrained decoding method called KCTS (Knowledge45;Constrained Tree Search) which guides a frozen LM to generate text aligned with the reference knowledge at each decoding step using a knowledge classifier score and MCTS (Monte45;Carlo Tree Search). To adapt the sequence45;level knowledge classifier to token45;level guidance we also propose a novel token45;level hallucination detection method called RIPA (Reward Inflection Point Approximation). Our empirical results on knowledge45;grounded dialogue and abstractive summarization demonstrate the strength of KCTS as a plug45;and45;play model45;agnostic decoding method that can effectively reduce hallucinations in natural language generation.
