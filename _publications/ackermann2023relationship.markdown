---
layout: publication
title: 'On The Relationship Between Skill Neurons And Robustness In Prompt Tuning'
authors: Leon Ackermann, Xenia Ohmer
conference: "Arxiv"
year: 2023
bibkey: ackermann2023relationship
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.12263"}
tags: ['Transformer', 'Model Architecture', 'Security', 'Pretraining Methods', 'BERT', 'Prompting']
---
Prompt Tuning is a popular parameter-efficient finetuning method for
pre-trained large language models (PLMs). Based on experiments with RoBERTa, it
has been suggested that Prompt Tuning activates specific neurons in the
transformer's feed-forward networks, that are highly predictive and selective
for the given task. In this paper, we study the robustness of Prompt Tuning in
relation to these "skill neurons", using RoBERTa and T5. We show that prompts
tuned for a specific task are transferable to tasks of the same type but are
not very robust to adversarial data. While prompts tuned for RoBERTa yield
below-chance performance on adversarial data, prompts tuned for T5 are slightly
more robust and retain above-chance performance in two out of three cases. At
the same time, we replicate the finding that skill neurons exist in RoBERTa and
further show that skill neurons also exist in T5. Interestingly, the skill
neurons of T5 determined on non-adversarial data are also among the most
predictive neurons on the adversarial data, which is not the case for RoBERTa.
We conclude that higher adversarial robustness may be related to a model's
ability to consistently activate the relevant skill neurons on adversarial
data.
