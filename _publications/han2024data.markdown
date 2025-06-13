---
layout: publication
title: 'Alignsum: Data Pyramid Hierarchical Fine-tuning For Aligning With Human Summarization Preference'
authors: Yang Han, Yiming Wang, Rui Wang, Lu Chen, Kai Yu
conference: "Arxiv"
year: 2024
bibkey: han2024data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.00409"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Text summarization tasks commonly employ Pre-trained Language Models (PLMs)
to fit diverse standard datasets. While these PLMs excel in automatic
evaluations, they frequently underperform in human evaluations, indicating a
deviation between their generated summaries and human summarization
preferences. This discrepancy is likely due to the low quality of fine-tuning
datasets and the limited availability of high-quality human-annotated data that
reflect true human preference. To address this challenge, we introduce a novel
human summarization preference alignment framework AlignSum. This framework
consists of three parts: Firstly, we construct a Data Pymarid with extractive,
abstractive, and human-annotated summary data. Secondly, we conduct the
Gaussian Resampling to remove summaries with extreme lengths. Finally, we
implement the two-stage hierarchical fine-tuning with Data Pymarid after
Gaussian Resampling. We apply AlignSum to PLMs on the human-annotated
CNN/DailyMail and BBC XSum datasets. Experiments show that with AlignSum, PLMs
like BART-Large surpass 175B GPT-3 in both automatic and human evaluations.
This demonstrates that AlignSum significantly enhances the alignment of
language models with human summarization preferences.
