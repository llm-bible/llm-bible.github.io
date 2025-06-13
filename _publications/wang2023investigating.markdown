---
layout: publication
title: 'Investigating The Learning Behaviour Of In-context Learning: A Comparison With Supervised Learning'
authors: Xindi Wang, Yufei Wang, Can Xu, Xiubo Geng, Bowen Zhang, Chongyang Tao, Frank Rudzicz, Robert E. Mercer, Daxin Jiang
conference: "Arxiv"
year: 2023
bibkey: wang2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.15411"}
tags: ['Prompting', 'Training Techniques', 'In-Context Learning']
---
Large language models (LLMs) have shown remarkable capacity for in-context
learning (ICL), where learning a new task from just a few training examples is
done without being explicitly pre-trained. However, despite the success of
LLMs, there has been little understanding of how ICL learns the knowledge from
the given prompts. In this paper, to make progress toward understanding the
learning behaviour of ICL, we train the same LLMs with the same demonstration
examples via ICL and supervised learning (SL), respectively, and investigate
their performance under label perturbations (i.e., noisy labels and label
imbalance) on a range of classification tasks. First, via extensive
experiments, we find that gold labels have significant impacts on the
downstream in-context performance, especially for large language models;
however, imbalanced labels matter little to ICL across all model sizes. Second,
when comparing with SL, we show empirically that ICL is less sensitive to label
perturbations than SL, and ICL gradually attains comparable performance to SL
as the model size increases.
