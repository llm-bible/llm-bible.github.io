---
layout: publication
title: Structural Pre-training For Dialogue Comprehension
authors: Zhang Zhuosheng, Zhao Hai
conference: "Arxiv"
year: 2021
bibkey: zhang2021structural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.10956"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Pre-trained language models (PrLMs) have demonstrated superior performance due to their strong ability to learn universal language representations from self-supervised pre-training. However even with the help of the powerful PrLMs it is still challenging to effectively capture task-related knowledge from dialogue texts which are enriched by correlations among speaker-aware utterances. In this work we present SPIDER Structural Pre-traIned DialoguE Reader to capture dialogue exclusive features. To simulate the dialogue-like features we propose two training objectives in addition to the original LM objectives 1) utterance order restoration which predicts the order of the permuted utterances in dialogue context; 2) sentence backbone regularization which regularizes the model to improve the factual correctness of summarized subject-verb-object triplets. Experimental results on widely used dialogue benchmarks verify the effectiveness of the newly introduced self-supervised tasks.
