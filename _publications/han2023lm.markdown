---
layout: publication
title: 'Lm-infinite: Zero-shot Extreme Length Generalization For Large Language Models'
authors: Han Chi, Wang Qifan, Peng Hao, Xiong Wenhan, Chen Yu, Ji Heng, Wang Sinong
conference: "Arxiv"
year: 2023
bibkey: han2023lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16137"}
  - {name: "Code", url: "https://github.com/Glaciohound/LM-Infinite"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
'Today''s large language models (LLMs) typically train on short text segments (e.g., <4K tokens) due to the quadratic complexity of their Transformer architectures. As a result, their performance suffers drastically on inputs longer than those encountered during training, substantially limiting their applications in real-world tasks involving long contexts such as encoding scientific articles, code repositories, or long dialogues. Through theoretical analysis and empirical investigation, this work identifies three major factors contributing to this length generalization failure. Our theoretical analysis further reveals that commonly used techniques like truncating the attention window or relative positional encodings are inadequate to address them. Answering these challenges, we propose LM-Infinite, a simple and effective method for enhancing LLMs'' capabilities of handling long contexts. LM-Infinite is highly flexible and can be used with most modern LLMs off-the-shelf. Without any parameter updates, it allows LLMs pre-trained with 2K or 4K-long segments to generalize to up to 200M length inputs while retaining perplexity. It also improves performance on downstream tasks such as Passkey Retrieval and Qasper in the zero-shot setting. LM-Infinite brings substantial efficiency improvements: it achieves 2.7x decoding speed up and 7.5x memory saving over the original model. Our codes are released at \url\{https://github.com/Glaciohound/LM-Infinite\}.'
