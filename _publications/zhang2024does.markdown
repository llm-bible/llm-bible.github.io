---
layout: publication
title: Mathverse Does Your Multi45;modal LLM Truly See The Diagrams In Visual Math Problems
authors: Zhang Renrui, Jiang Dongzhi, Zhang Yichi, Lin Haokun, Guo Ziyu, Qiu Pengshuo, Zhou Aojun, Lu Pan, Chang Kai-wei, Gao Peng, Li Hongsheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14624"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods']
---
The remarkable progress of Multi45;modal Large Language Models (MLLMs) has garnered unparalleled attention due to their superior performance in visual contexts. However their capabilities in visual math problem45;solving remain insufficiently evaluated and understood. We investigate current benchmarks to incorporate excessive visual content within textual questions which potentially assist MLLMs in deducing answers without truly interpreting the input diagrams. To this end we introduce MathVerse an all45;around visual math benchmark designed for an equitable and in45;depth evaluation of MLLMs. We meticulously collect 2612 high45;quality multi45;subject math problems with diagrams from publicly available sources. Each problem is then transformed by human annotators into six distinct versions each offering varying degrees of information content in multi45;modality contributing to 15K test samples in total. This approach allows MathVerse to comprehensively assess whether and how much MLLMs can truly understand the visual diagrams for mathematical reasoning. In addition we propose a Chain45;of45;Thought (CoT) evaluation strategy for a fine45;grained assessment of the output answers. Rather than naively judging True or False we employ GPT45;4(V) to adaptively extract crucial reasoning steps and then score each step with detailed error analysis which can reveal the intermediate CoT reasoning quality by MLLMs. We hope the MathVerse benchmark may provide unique insights to guide the future development of MLLMs. Project page https://mathverse&#45;cuhk.github.io
