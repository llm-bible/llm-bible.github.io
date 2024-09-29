---
layout: publication
title: Lm45;infinite Zero45;shot Extreme Length Generalization For Large Language Models
authors: Han Chi, Wang Qifan, Peng Hao, Xiong Wenhan, Chen Yu, Ji Heng, Wang Sinong
conference: "Arxiv"
year: 2023
bibkey: han2023lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16137"}
  - {name: "Code", url: "https://github.com/Glaciohound/LM&#45;Infinite&#125;"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Todays large language models (LLMs) typically train on short text segments (e.g. <4K tokens) due to the quadratic complexity of their Transformer architectures. As a result their performance suffers drastically on inputs longer than those encountered during training substantially limiting their applications in real45;world tasks involving long contexts such as encoding scientific articles code repositories or long dialogues. Through theoretical analysis and empirical investigation this work identifies three major factors contributing to this length generalization failure. Our theoretical analysis further reveals that commonly used techniques like truncating the attention window or relative positional encodings are inadequate to address them. Answering these challenges we propose LM45;Infinite a simple and effective method for enhancing LLMs capabilities of handling long contexts. LM45;Infinite is highly flexible and can be used with most modern LLMs off45;the45;shelf. Without any parameter updates it allows LLMs pre45;trained with 2K or 4K45;long segments to generalize to up to 200M length inputs while retaining perplexity. It also improves performance on downstream tasks such as Passkey Retrieval and Qasper in the zero45;shot setting. LM45;Infinite brings substantial efficiency improvements it achieves 2.7x decoding speed up and 7.5x memory saving over the original model. Our codes are released at url123;https://github.com/Glaciohound/LM&#45;Infinite&#125;.
