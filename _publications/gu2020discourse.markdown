---
layout: publication
title: Dialogbert Discourse-aware Response Generation Via Learning To Recover And Rank Utterances
authors: Gu Xiaodong, Yoo Kang Min, Ha Jung-woo
conference: "Arxiv"
year: 2020
bibkey: gu2020discourse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.01775"}
tags: ['Attention Mechanism', 'BERT', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent advances in pre-trained language models have significantly improved neural response generation. However existing methods usually view the dialogue context as a linear sequence of tokens and learn to generate the next word through token-level self-attention. Such token-level encoding hinders the exploration of discourse-level coherence among utterances. This paper presents DialogBERT a novel conversational response generation model that enhances previous PLM-based dialogue models. DialogBERT employs a hierarchical Transformer architecture. To efficiently capture the discourse-level coherence among utterances we propose two training objectives including masked utterance regression and distributed utterance order ranking in analogy to the original BERT training. Experiments on three multi-turn conversation datasets show that our approach remarkably outperforms the baselines such as BART and DialoGPT in terms of quantitative evaluation. The human evaluation suggests that DialogBERT generates more coherent informative and human-like responses than the baselines with significant margins.
