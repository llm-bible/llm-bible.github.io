---
layout: publication
title: Less Is More For Improving Automatic Evaluation Of Factual Consistency
authors: Wang Tong, Kulkarni Ninad, Qi Yanjun
conference: "Arxiv"
year: 2024
bibkey: wang2024less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06579"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
Assessing the factual consistency of automatically generated texts in relation to source context is crucial for developing reliable natural language generation applications. Recent literature proposes AlignScore which uses a unified alignment model to evaluate factual consistency and substantially outperforms previous methods across many benchmark tasks. In this paper we take a closer look of datasets used in AlignScore and uncover an unexpected finding utilizing a smaller number of data points can actually improve performance. We process the original AlignScore training dataset to remove noise augment with robustness-enhanced samples and utilize a subset comprising 1037; of the data to train an improved factual consistency evaluation model we call LIM-RA (Less Is More for Robust AlignScore). LIM-RA demonstrates superior performance consistently outperforming AlignScore and other strong baselines like ChatGPT across four benchmarks (two utilizing traditional natural language generation datasets and two focused on large language model outputs). Our experiments show that LIM-RA achieves the highest score on 24 of the 33 test datasets while staying competitive on the rest establishing the new state-of-the-art benchmarks.
