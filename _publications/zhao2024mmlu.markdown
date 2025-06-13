---
layout: publication
title: 'MMLU-CF: A Contamination-free Multi-task Language Understanding Benchmark'
authors: Qihao Zhao, Yangyu Huang, Tengchao Lv, Lei Cui, Qinzheng Sun, Shaoguang Mao, Xin Zhang, Ying Xin, Qiufeng Yin, Scarlett Li, Furu Wei
conference: "Arxiv"
year: 2024
bibkey: zhao2024mmlu
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15194'}
  - {name: "Code", url: 'https://github.com/microsoft/MMLU-CF'}
  - {name: "Code", url: 'https://huggingface.co/datasets/microsoft/MMLU-CF'}
tags: ['Has Code', 'Training Techniques', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Multiple-choice question (MCQ) datasets like Massive Multitask Language
Understanding (MMLU) are widely used to evaluate the commonsense,
understanding, and problem-solving abilities of large language models (LLMs).
However, the open-source nature of these benchmarks and the broad sources of
training data for LLMs have inevitably led to benchmark contamination,
resulting in unreliable evaluation results. To alleviate this issue, we propose
a contamination-free and more challenging MCQ benchmark called MMLU-CF. This
benchmark reassesses LLMs' understanding of world knowledge by averting both
unintentional and malicious data leakage. To avoid unintentional data leakage,
we source data from a broader domain and design three decontamination rules. To
prevent malicious data leakage, we divide the benchmark into validation and
test sets with similar difficulty and subject distributions. The test set
remains closed-source to ensure reliable results, while the validation set is
publicly available to promote transparency and facilitate independent
verification. Our evaluation of mainstream LLMs reveals that the powerful
GPT-4o achieves merely a 5-shot score of 73.4% and a 0-shot score of 71.9% on
the test set, which indicates the effectiveness of our approach in creating a
more rigorous and contamination-free evaluation standard. The GitHub repository
is available at https://github.com/microsoft/MMLU-CF and the dataset refers to
https://huggingface.co/datasets/microsoft/MMLU-CF.
