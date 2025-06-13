---
layout: publication
title: 'Llmrefine: Pinpointing And Refining Large Language Models Via Fine-grained Actionable Feedback'
authors: Wenda Xu, Daniel Deutsch, Mara Finkelstein, Juraj Juraska, Biao Zhang, Zhongtao Liu, William Yang Wang, Lei Li, Markus Freitag
conference: "Arxiv"
year: 2023
bibkey: xu2023pinpointing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09336'}
tags: ['Language Modeling', 'RAG', 'Efficiency and Optimization', 'Applications', 'Fine-Tuning']
---
Recent large language models (LLM) are leveraging human feedback to improve
their generation quality. However, human feedback is costly to obtain,
especially during inference. In this work, we propose LLMRefine, an inference
time optimization method to refine LLM's output. The core idea is to use a
learned fine-grained feedback model to pinpoint defects and guide LLM to refine
them iteratively. Using original LLM as a proposal of edits, LLMRefine searches
for defect-less text via simulated annealing, trading off the exploration and
exploitation. We conduct experiments on three text generation tasks, including
machine translation, long-form question answering (QA), and topical
summarization. LLMRefine consistently outperforms all baseline approaches,
achieving improvements up to 1.7 MetricX points on translation tasks, 8.1
ROUGE-L on ASQA, 2.2 ROUGE-L on topical summarization.
