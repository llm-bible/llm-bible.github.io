---
layout: publication
title: 'Longreason: A Synthetic Long-context Reasoning Benchmark Via Context Expansion'
authors: Zhan Ling, Kang Liu, Kai Yan, Yifan Yang, Weijian Lin, Ting-han Fan, Lingfeng Shen, Zhengyin Du, Jiecao Chen
conference: "Arxiv"
year: 2025
bibkey: ling2025synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15089"}
tags: ['Reinforcement Learning']
---
Large language models (LLMs) have demonstrated remarkable progress in
understanding long-context inputs. However, benchmarks for evaluating the
long-context reasoning abilities of LLMs fall behind the pace. Existing
benchmarks often focus on a narrow range of tasks or those that do not demand
complex reasoning. To address this gap and enable a more comprehensive
evaluation of the long-context reasoning capabilities of current LLMs, we
propose a new synthetic benchmark, LongReason, which is constructed by
synthesizing long-context reasoning questions from a varied set of
short-context reasoning questions through context expansion. LongReason
consists of 794 multiple-choice reasoning questions with diverse reasoning
patterns across three task categories: reading comprehension, logical
inference, and mathematical word problems. We evaluate 21 LLMs on LongReason,
revealing that most models experience significant performance drops as context
length increases. Our further analysis shows that even state-of-the-art LLMs
still have significant room for improvement in providing robust reasoning
across different tasks. We have open-sourced LongReason under
https://huggingface.co/datasets/lz1bytedance/LongReason to support the
comprehensive evaluation of LLMs' long-context reasoning capabilities.
