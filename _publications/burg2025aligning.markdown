---
layout: publication
title: 'Aligning Black-box Language Models With Human Judgments'
authors: Gerrit J. J. Van Den Burg, Gen Suzuki, Wei Liu, Murat Sensoy
conference: "Arxiv"
year: 2025
bibkey: burg2025aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04997"}
tags: ['Fine-Tuning', 'Tools', 'Ethics and Bias', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Few-Shot']
---
Large language models (LLMs) are increasingly used as automated judges to
evaluate recommendation systems, search engines, and other subjective tasks,
where relying on human evaluators can be costly, time-consuming, and
unscalable. LLMs offer an efficient solution for continuous, automated
evaluation. However, since the systems that are built and improved with these
judgments are ultimately designed for human use, it is crucial that LLM
judgments align closely with human evaluators to ensure such systems remain
human-centered. On the other hand, aligning LLM judgments with human evaluators
is challenging due to individual variability and biases in human judgments. We
propose a simple yet effective framework to align LLM judgments with individual
human evaluators or their aggregated judgments, without retraining or
fine-tuning the LLM. Our approach learns a linear mapping between the LLM's
outputs and human judgments, achieving over 142% average improvement in
agreement across 29 tasks with only a small number of calibration examples used
for training. Notably, our method works in zero-shot and few-shot settings,
exceeds inter-human agreement on four out of six tasks, and enables smaller
LLMs to achieve performance comparable to that of larger models.
