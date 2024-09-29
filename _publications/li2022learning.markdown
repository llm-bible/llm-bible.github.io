---
layout: publication
title: Learning To Transfer Prompts For Text Generation
authors: Li Junyi, Tang Tianyi, Nie Jian-yun, Wen Ji-rong, Zhao Wayne Xin
conference: "Arxiv"
year: 2022
bibkey: li2022learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.01543"}
  - {name: "Code", url: "https://github.com/RUCAIBox/Transfer&#45;Prompts&#45;for&#45;Text&#45;Generation"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Prompting', 'Transformer']
---
Pretrained language models (PLMs) have made remarkable progress in text generation tasks via fine45;tuning. While it is challenging to fine45;tune PLMs in a data45;scarce situation. Therefore it is non45;trivial to develop a general and lightweight model that can adapt to various text generation tasks based on PLMs. To fulfill this purpose the recent prompt45;based learning offers a potential solution. In this paper we improve this technique and propose a novel prompt45;based method (PTG) for text generation in a transferable setting. First PTG learns a set of source prompts for various source generation tasks and then transfers these prompts as target prompts to perform target generation tasks. To consider both task45; and instance45;level information we design an adaptive attention mechanism to derive the target prompts. For each data instance PTG learns a specific target prompt by attending to highly relevant source prompts. In extensive experiments PTG yields competitive or better results than fine45;tuning methods. We release our source prompts as an open resource where users can add or reuse them to improve new text generation tasks for future research. Code and data can be available at https://github.com/RUCAIBox/Transfer&#45;Prompts&#45;for&#45;Text&#45;Generation.
