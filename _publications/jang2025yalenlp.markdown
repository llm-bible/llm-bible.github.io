---
layout: publication
title: 'Yalenlp @ Peranssumm 2025: Multi-perspective Integration Via Mixture-of-agents For Enhanced Healthcare QA Summarization'
authors: Dongsuk Jang, Alan Li, Arman Cohan
conference: "Arxiv"
year: 2025
bibkey: jang2025yalenlp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03932"}
tags: ['Agentic', 'Model Architecture', 'Training Techniques', 'Few-Shot', 'Tools', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Prompting', 'Applications', 'In-Context Learning']
---
Automated summarization of healthcare community question-answering forums is
challenging due to diverse perspectives presented across multiple user
responses to each question. The PerAnsSumm Shared Task was therefore proposed
to tackle this challenge by identifying perspectives from different answers and
then generating a comprehensive answer to the question. In this study, we
address the PerAnsSumm Shared Task using two complementary paradigms: (i) a
training-based approach through QLoRA fine-tuning of LLaMA-3.3-70B-Instruct,
and (ii) agentic approaches including zero- and few-shot prompting with
frontier LLMs (LLaMA-3.3-70B-Instruct and GPT-4o) and a Mixture-of-Agents (MoA)
framework that leverages a diverse set of LLMs by combining outputs from
multi-layer feedback aggregation. For perspective span
identification/classification, GPT-4o zero-shot achieves an overall score of
0.57, substantially outperforming the 0.40 score of the LLaMA baseline. With a
2-layer MoA configuration, we were able to improve LLaMA performance up by 28
percent to 0.51. For perspective-based summarization, GPT-4o zero-shot attains
an overall score of 0.42 compared to 0.28 for the best LLaMA zero-shot, and our
2-layer MoA approach boosts LLaMA performance by 32 percent to 0.37.
Furthermore, in few-shot setting, our results show that the
sentence-transformer embedding-based exemplar selection provides more gain than
manually selected exemplars on LLaMA models, although the few-shot prompting is
not always helpful for GPT-4o. The YaleNLP team's approach ranked the overall
second place in the shared task.
