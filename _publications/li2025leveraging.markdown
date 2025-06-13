---
layout: publication
title: 'Leveraging Llms As Meta-judges: A Multi-agent Framework For Evaluating LLM Judgments'
authors: Yuran Li, Jama Hussein Mohamud, Chongren Sun, Di Wu, Benoit Boulet
conference: "Arxiv"
year: 2025
bibkey: li2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17087"}
tags: ['Agentic', 'GPT', 'Tools', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) are being widely applied across various fields,
but as tasks become more complex, evaluating their responses is increasingly
challenging. Compared to human evaluators, the use of LLMs to support
performance evaluation offers a more efficient alternative. However, most
studies focus mainly on aligning LLMs' judgments with human preferences,
overlooking the existence of biases and mistakes in human judgment.
Furthermore, how to select suitable LLM judgments given multiple potential LLM
responses remains underexplored. To address these two aforementioned issues, we
propose a three-stage meta-judge selection pipeline: 1) developing a
comprehensive rubric with GPT-4 and human experts, 2) using three advanced LLM
agents to score judgments, and 3) applying a threshold to filter out
low-scoring judgments. Compared to methods using a single LLM as both judge and
meta-judge, our pipeline introduces multi-agent collaboration and a more
comprehensive rubric. Experimental results on the JudgeBench dataset show about
15.55% improvement compared to raw judgments and about 8.37% improvement over
the single-agent baseline. Our work demonstrates the potential of LLMs as
meta-judges and lays the foundation for future research on constructing
preference datasets for LLM-as-a-judge reinforcement learning.
