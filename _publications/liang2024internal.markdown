---
layout: publication
title: "Internal Consistency And Self-feedback In Large Language Models: A Survey"
authors: Liang Xun, Song Shichao, Zheng Zifan, Wang Hanyu, Yu Qingchen, Li Xunkai, Li Rong-hua, Cheng Peng, Wang Zhonghao, Xiong Feiyu, Li Zhiyu
conference: "Arxiv"
year: 2024
bibkey: liang2024internal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14507"}
  - {name: "Code", url: "https://github.com/IAAR-Shanghai/ICSFSurvey"}
tags: ['Applications', 'Has Code', 'Interpretability And Explainability', 'RAG', 'Survey Paper', 'Tools']
---
Large language models (LLMs) often exhibit deficient reasoning or generate hallucinations. To address these studies prefixed with Self- such as Self-Consistency Self-Improve and Self-Refine have been initiated. They share a commonality involving LLMs evaluating and updating themselves. Nonetheless these efforts lack a unified perspective on summarization as existing surveys predominantly focus on categorization. In this paper we summarize a theoretical framework Internal Consistency offering explanations for reasoning deficiencies and hallucinations. Internal Consistency refers to the consistency in expressions among LLMs latent decoding or response layers based on sampling methodologies. Then we introduce another effective theoretical framework capable of mining Internal Consistency named Self-Feedback. This framework consists of two modules Self-Evaluation and Self-Update. The former captures Internal Consistency Signals while the latter leverages the signals to enhance either the models response or the model itself. This framework has been employed in numerous studies. We systematically classify these studies by tasks and lines of work; summarize relevant evaluation methods and benchmarks; and delve into the concern Does Self-Feedback Really Work We also propose several critical viewpoints including the Hourglass Evolution of Internal Consistency Consistency Is (Almost) Correctness hypothesis and The Paradox of Latent and Explicit Reasoning. The relevant resources are open-sourced at https://github.com/IAAR-Shanghai/ICSFSurvey."
