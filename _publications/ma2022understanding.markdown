---
layout: publication
title: Understanding And Mitigating Overfitting In Prompt Tuning For Vision-language
  Models
authors: Chengcheng Ma et al.
conference: Arxiv
year: 2022
citations: 39
bibkey: ma2022understanding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.02219'}, {name: Code,
    url: 'https://tinyurl.com/mpe64f89'}]
tags: [Multimodal Models, Prompting, Efficiency and Optimization]
---
Pretrained vision-language models (VLMs) such as CLIP have shown impressive
generalization capability in downstream vision tasks with appropriate text
prompts. Instead of designing prompts manually, Context Optimization (CoOp) has
been recently proposed to learn continuous prompts using taskspecific training
data. Despite the performance improvements on downstream tasks, several studies
have reported that CoOp suffers from the overfitting issue in two aspects: (i)
the test accuracy on base classes first improves and then worsens during
training;(ii) the test accuracy on novel classes keeps decreasing. However,
none of the existing studies can understand and mitigate such overfitting
problems. In this study, we first explore the cause of overfitting by analyzing
the gradient flow. Comparative experiments reveal that CoOp favors
generalizable and spurious features in the early and later training stages,
respectively, leading to the non-overfitting and overfitting phenomena. Given
those observations, we propose Subspace Prompt Tuning (SubPT) to project the
gradients in back-propagation onto the low-rank subspace spanned by the
early-stage gradient flow eigenvectors during the entire training process and
successfully eliminate the overfitting problem. In addition, we equip CoOp with
a Novel Feature Learner (NFL) to enhance the generalization ability of the
learned prompts onto novel categories beyond the training set, needless of
image training data. Extensive experiments on 11 classification datasets
demonstrate that SubPT+NFL consistently boost the performance of CoOp and
outperform the state-of-the-art CoCoOp approach. Experiments on more
challenging vision downstream tasks, including open-vocabulary object detection
and zero-shot semantic segmentation, also verify the effectiveness of the
proposed method. Codes can be found at https://tinyurl.com/mpe64f89.