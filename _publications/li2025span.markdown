---
layout: publication
title: 'Span-level Emotion-cause-category Triplet Extraction With Instruction Tuning Llms And Data Augmentation'
authors: Xiangju Li, Dong Yang, Xiaogang Zhu, Faliang Huang, Peng Zhang, Zhongying Zhao
conference: "Arxiv"
year: 2025
bibkey: li2025span
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12331"}
  - {name: "Code", url: "https://github.com/zxgnlp/InstruDa-LLM"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
Span-level emotion-cause-category triplet extraction represents a novel and
complex challenge within emotion cause analysis. This task involves identifying
emotion spans, cause spans, and their associated emotion categories within the
text to form structured triplets. While prior research has predominantly
concentrated on clause-level emotion-cause pair extraction and span-level
emotion-cause detection, these methods often confront challenges originating
from redundant information retrieval and difficulty in accurately determining
emotion categories, particularly when emotions are expressed implicitly or
ambiguously. To overcome these challenges, this study explores a fine-grained
approach to span-level emotion-cause-category triplet extraction and introduces
an innovative framework that leverages instruction tuning and data augmentation
techniques based on large language models. The proposed method employs
task-specific triplet extraction instructions and utilizes low-rank adaptation
to fine-tune large language models, eliminating the necessity for intricate
task-specific architectures. Furthermore, a prompt-based data augmentation
strategy is developed to address data scarcity by guiding large language models
in generating high-quality synthetic training data. Extensive experimental
evaluations demonstrate that the proposed approach significantly outperforms
existing baseline methods, achieving at least a 12.8% improvement in span-level
emotion-cause-category triplet extraction metrics. The results demonstrate the
method's effectiveness and robustness, offering a promising avenue for
advancing research in emotion cause analysis. The source code is available at
https://github.com/zxgnlp/InstruDa-LLM.
