---
layout: publication
title: 'Code-switching Curriculum Learning For Multilingual Transfer In Llms'
authors: Haneul Yoo, Cheonbok Park, Sangdoo Yun, Alice Oh, Hwaran Lee
conference: "Arxiv"
year: 2024
bibkey: yoo2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02460"}
tags: ['Responsible AI', 'Pre-Training', 'Tools', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) now exhibit near human-level performance in
various tasks, but their performance drops drastically after a handful of
high-resource languages due to the imbalance in pre-training data. Inspired by
the human process of second language acquisition, particularly code-switching
(the practice of language alternation in a conversation), we propose
code-switching curriculum learning (CSCL) to enhance cross-lingual transfer for
LLMs. CSCL mimics the stages of human language learning by progressively
training models with a curriculum consisting of 1) token-level code-switching,
2) sentence-level code-switching, and 3) monolingual corpora. Using Qwen 2 as
our underlying model, we demonstrate the efficacy of the CSCL in improving
language transfer to Korean, achieving significant performance gains compared
to monolingual continual pre-training methods. Ablation studies reveal that
both token- and sentence-level code-switching significantly enhance
cross-lingual transfer and that curriculum learning amplifies these effects. We
also extend our findings into various languages, including Japanese
(high-resource) and Indonesian (low-resource), and using two additional models
(Gemma 2 and Phi 3.5). We further show that CSCL mitigates spurious
correlations between language resources and safety alignment, presenting a
robust, efficient framework for more equitable language transfer in LLMs. We
observe that CSCL is effective for low-resource settings where high-quality,
monolingual corpora for language transfer are hardly available.
