---
layout: publication
title: 'Salute The Classic: Revisiting Challenges Of Machine Translation In The Age Of Large Language Models'
authors: Jianhui Pang, Fanghua Ye, Longyue Wang, Dian Yu, Derek F. Wong, Shuming Shi, Zhaopeng Tu
conference: "Arxiv"
year: 2024
bibkey: pang2024salute
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08350"}
  - {name: "Code", url: "https://github.com/pangjh3/LLM4MT"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Has Code', 'Applications', 'Attention Mechanism']
---
The evolution of Neural Machine Translation (NMT) has been significantly
influenced by six core challenges (Koehn and Knowles, 2017), which have acted
as benchmarks for progress in this field. This study revisits these challenges,
offering insights into their ongoing relevance in the context of advanced Large
Language Models (LLMs): domain mismatch, amount of parallel data, rare word
prediction, translation of long sentences, attention model as word alignment,
and sub-optimal beam search. Our empirical findings indicate that LLMs
effectively lessen the reliance on parallel data for major languages in the
pretraining phase. Additionally, the LLM-based translation system significantly
enhances the translation of long sentences that contain approximately 80 words
and shows the capability to translate documents of up to 512 words. However,
despite these significant improvements, the challenges of domain mismatch and
prediction of rare words persist. While the challenges of word alignment and
beam search, specifically associated with NMT, may not apply to LLMs, we
identify three new challenges for LLMs in translation tasks: inference
efficiency, translation of low-resource languages in the pretraining phase, and
human-aligned evaluation. The datasets and models are released at
https://github.com/pangjh3/LLM4MT.
