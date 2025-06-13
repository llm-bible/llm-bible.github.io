---
layout: publication
title: 'Generative Data Augmentation Using Llms Improves Distributional Robustness In Question Answering'
authors: Arijit Ghosh Chowdhury, Aman Chadha
conference: "Arxiv"
year: 2023
bibkey: chowdhury2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06358"}
tags: ['Fine-Tuning', 'Applications', 'Model Architecture', 'Security', 'Attention Mechanism']
---
Robustness in Natural Language Processing continues to be a pertinent issue,
where state of the art models under-perform under naturally shifted
distributions. In the context of Question Answering, work on domain adaptation
methods continues to be a growing body of research. However, very little
attention has been given to the notion of domain generalization under natural
distribution shifts, where the target domain is unknown. With drastic
improvements in the quality and access to generative models, we answer the
question: How do generated datasets influence the performance of QA models
under natural distribution shifts? We perform experiments on 4 different
datasets under varying amounts of distribution shift, and analyze how
"in-the-wild" generation can help achieve domain generalization. We take a
two-step generation approach, generating both contexts and QA pairs to augment
existing datasets. Through our experiments, we demonstrate how augmenting
reading comprehension datasets with generated data leads to better robustness
towards natural distribution shifts.
