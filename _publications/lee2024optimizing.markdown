---
layout: publication
title: LRQ Optimizing Post45;training Quantization For Large Language Models By Learning Low45;rank Weight45;scaling Matrices
authors: Lee Jung Hyun, Kim Jeonghoon, Yang June Yong, Kwon Se Jung, Yang Eunho, Yoo Kang Min, Lee Dongsoo
conference: "Arxiv"
year: 2024
bibkey: lee2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11534"}
  - {name: "Code", url: "https://github.com/onliwad101/FlexRound&#95;LRQ&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
With the commercialization of large language models (LLMs) weight45;activation quantization has emerged to compress and accelerate LLMs achieving high throughput while reducing inference costs. However existing post45;training quantization (PTQ) techniques for quantizing weights and activations of LLMs still suffer from non45;negligible accuracy drops especially on massive multitask language understanding. To address this issue we propose Low45;Rank Quantization (LRQ) 45; a simple yet effective post45;training weight quantization method for LLMs that reconstructs the outputs of an intermediate Transformer block by leveraging low45;rank weight45;scaling matrices replacing the conventional full weight45;scaling matrices that entail as many learnable scales as their associated weights. Thanks to parameter sharing via low45;rank structure LRQ only needs to learn significantly fewer parameters while enabling the individual scaling of weights thus boosting the generalization capability of quantized LLMs. We show the superiority of LRQ over prior LLM PTQ works under (i) 845;bit weight and per45;tensor activation quantization (ii) 445;bit weight and 845;bit per45;token activation quantization and (iii) low45;bit weight45;only quantization schemes. Our code is available at url123;https://github.com/onliwad101/FlexRound&#95;LRQ&#125; to inspire LLM researchers and engineers.
