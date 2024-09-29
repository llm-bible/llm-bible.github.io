---
layout: publication
title: Let the Code LLM Edit Itself When You Edit the Code
authors: He Zhenyu, Zhang Jun, Luo Shengjie, Xu Jingjing, Zhang Zhi, He Di
conference: "Arxiv"
year: 2024
bibkey: he2024let
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03157"}
tags: ['Applications', 'Efficiency And Optimization', 'Merging', 'Reinforcement Learning']
---
In this work we investigate a typical scenario in code generation where a developer edits existing code in real time and requests a code assistant e.g. a large language model to re-predict the next token or next line on the fly. Naively the LLM needs to re-encode the entire KV cache to provide an accurate prediction. However this process is computationally expensive especially when the sequence length is long. Simply encoding the edited subsequence and integrating it to the original KV cache meets the temporal confusion problem leading to significantly worse performance. We address this efficiency and accuracy trade-off by introducing (PIE). Building upon the rotary positional encoding PIE first removes the rotary matrices in the Key cache that introduce temporal confusion and then reapplies the correct rotary matrices. This process ensures that positional relationships between tokens are correct and requires only a single round of matrix multiplication. We validate the effectiveness of PIE through extensive experiments on the RepoBench-C-8k dataset utilizing DeepSeek-Coder models with 1.3B 6.7B and 33B parameters. Our evaluation includes three real-world coding tasks code insertion code deletion and multi-place code editing. Results demonstrate that PIE reduces computational overhead by over 85 compared to the standard full recomputation approach across all model sizes and tasks while well approximating the model performance.
