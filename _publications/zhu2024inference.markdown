---
layout: publication
title: 'Inference-time Decontamination: Reusing Leaked Benchmarks For Large Language Model Evaluation'
authors: Zhu Qin, Cheng Qingyuan, Peng Runyu, Li Xiaonan, Liu Tengxiao, Peng Ru, Qiu Xipeng, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: zhu2024inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13990"}
tags: ['Applications', 'Pretraining Methods', 'Training Techniques']
---
"The training process of large language models (LLMs) often involves varying degrees of test data contamination. Although current LLMs are achieving increasingly better performance on various benchmarks, their performance in practical applications does not always match their benchmark results. Leakage of benchmarks can prevent the accurate assessment of LLMs' true performance. However, constructing new benchmarks is costly, labor-intensive and still carries the risk of leakage. Therefore, in this paper, we ask the question, Can we reuse these leaked benchmarks for LLM evaluation? We propose Inference-Time Decontamination (ITD) to address this issue by detecting and rewriting leaked samples without altering their difficulties. ITD can mitigate performance inflation caused by memorizing leaked benchmarks. Our proof-of-concept experiments demonstrate that ITD reduces inflated accuracy by 22.9&#37; on GSM8K and 19.0&#37; on MMLU. On MMLU, using Inference-time Decontamination can lead to a decrease in the results of Phi3 and Mistral by 6.7&#37; and 3.6&#37; respectively. We hope that ITD can provide more truthful evaluation results for large language models."
