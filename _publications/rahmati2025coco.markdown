---
layout: publication
title: 'Coco-cola: Evaluating And Improving Language Adherence In Multilingual Llms'
authors: Elnaz Rahmati, Alireza S. Ziabari, Morteza Dehghani
conference: "Arxiv"
year: 2025
bibkey: rahmati2025coco
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12476'}
tags: ['Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Multilingual Large Language Models (LLMs) develop cross-lingual abilities despite being trained on limited parallel data. However, they often struggle to generate responses in the intended language, favoring high-resource languages such as English. In this work, we introduce CoCo-CoLa (Correct Concept - Correct Language), a novel metric to evaluate language adherence in multilingual LLMs. Using fine-tuning experiments on a closed-book QA task across seven languages, we analyze how training in one language affects others' performance. Our findings reveal that multilingual models share task knowledge across languages but exhibit biases in the selection of output language. We identify language-specific layers, showing that final layers play a crucial role in determining output language. Accordingly, we propose a partial training strategy that selectively fine-tunes key layers, improving language adherence while significantly reducing computational cost. Our method achieves comparable or superior performance to full fine-tuning, particularly for low-resource languages, offering a more efficient multilingual adaptation.
