---
layout: publication
title: 'Unlearn What You Want To Forget: Efficient Unlearning For Llms'
authors: Jiaao Chen, Diyi Yang
conference: Arxiv
year: 2023
citations: 15
bibkey: chen2023unlearn
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.20150'}]
tags: [Transformer, Pre-Training, Training Techniques]
---
Large language models (LLMs) have achieved significant progress from
pre-training on and memorizing a wide range of textual data, however, this
process might suffer from privacy issues and violations of data protection
regulations. As a result, the ability to easily remove data related to
individual users from such models while not deteriorating their predictive
quality after the removal becomes increasingly important. To address these
issues, in this work, we propose an efficient unlearning framework that could
efficiently update LLMs without having to retrain the whole model after data
removals, by introducing lightweight unlearning layers learned with a selective
teacher-student objective into the transformers. In addition, we introduce a
fusion mechanism to effectively combine different unlearning layers that learns
to forget different sets of data to handle a sequence of forgetting operations.
Experiments on classification and generation tasks demonstrate the
effectiveness of our proposed methods compared to the state-of-the-art
baselines.