---
layout: publication
title: 'Toolace-r: Tool Learning With Adaptive Self-refinement'
authors: Xingshan Zeng, Weiwen Liu, Xu Huang, Zezhong Wang, Lingzhi Wang, Liangyou Li, Yasheng Wang, Lifeng Shang, Xin Jiang, Ruiming Tang, Qun Liu
conference: "Arxiv"
year: 2025
bibkey: zeng2025toolace
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01400'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Tool learning, which allows Large Language Models (LLMs) to leverage external
tools for solving complex user tasks, has emerged as a promising avenue for
extending model capabilities. However, current approaches primarily focus on
data synthesis for fine-tuning LLMs to invoke tools effectively, largely
ignoring how to fully stimulate the potential of the model. In this paper, we
propose ToolACE-R, a novel method that introduces adaptive self-refinement for
tool invocations. Our approach features a model-aware iterative training
procedure that progressively incorporates more training samples based on the
model's evolving capabilities. Additionally, it allows LLMs to iteratively
refine their tool calls, optimizing performance without requiring external
feedback. To further enhance computational efficiency, we integrate an adaptive
mechanism when scaling the inference time, enabling the model to autonomously
determine when to stop the refinement process. We conduct extensive experiments
across several benchmark datasets, showing that ToolACE-R achieves competitive
performance compared to advanced API-based models, even without any refinement.
Furthermore, its performance can be further improved efficiently through
adaptive self-refinement. Our results demonstrate the effectiveness of the
proposed method, which is compatible with base models of various sizes,
offering a promising direction for more efficient tool learning.
