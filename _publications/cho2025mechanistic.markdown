---
layout: publication
title: 'Mechanistic Fine-tuning For In-context Learning'
authors: Hakaze Cho, Peng Luo, Mariko Kato, Rin Kaenbyou, Naoya Inoue
conference: "Arxiv"
year: 2025
bibkey: cho2025mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14233"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability and Explainability', 'Model Architecture', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
In-context Learning (ICL) utilizes structured demonstration-query inputs to induce few-shot learning on Language Models (LMs), which are not originally pre-trained on ICL-style data. To bridge the gap between ICL and pre-training, some approaches fine-tune LMs on large ICL-style datasets by an end-to-end paradigm with massive computational costs. To reduce such costs, in this paper, we propose Attention Behavior Fine-Tuning (ABFT), utilizing the previous findings on the inner mechanism of ICL, building training objectives on the attention scores instead of the final outputs, to force the attention scores to focus on the correct label tokens presented in the context and mitigate attention scores from the wrong label tokens. Our experiments on 9 modern LMs and 8 datasets empirically find that ABFT outperforms in performance, robustness, unbiasedness, and efficiency, with only around 0.01% data cost compared to the previous methods. Moreover, our subsequent analysis finds that the end-to-end training objective contains the ABFT objective, suggesting the implicit bias of ICL-style data to the emergence of induction heads. Our work demonstrates the possibility of controlling specific module sequences within LMs to improve their behavior, opening up the future application of mechanistic interpretability.
