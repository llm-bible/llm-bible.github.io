---
layout: publication
title: 'Comparing Test Sets With Item Response Theory'
authors: Vania Clara, Htut Phu Mon, Huang William, Mungra Dhara, Pang Richard Yuanzhe, Phang Jason, Liu Haokun, Cho Kyunghyun, Bowman Samuel R.
conference: "Arxiv"
year: 2021
bibkey: vania2021comparing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.00840"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent years have seen numerous NLP datasets introduced to evaluate the
performance of fine-tuned models on natural language understanding tasks.
Recent results from large pretrained models, though, show that many of these
datasets are largely saturated and unlikely to be able to detect further
progress. What kind of datasets are still effective at discriminating among
strong models, and what kind of datasets should we expect to be able to detect
future improvements? To measure this uniformly across datasets, we draw on Item
Response Theory and evaluate 29 datasets using predictions from 18 pretrained
Transformer models on individual test examples. We find that Quoref, HellaSwag,
and MC-TACO are best suited for distinguishing among state-of-the-art models,
while SNLI, MNLI, and CommitmentBank seem to be saturated for current strong
models. We also observe span selection task format, which is used for QA
datasets like QAMR or SQuAD2.0, is effective in differentiating between strong
and weak models.
