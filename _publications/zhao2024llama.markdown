---
layout: publication
title: 'Llama Beyond English: An Empirical Study On Language Capability Transfer'
authors: Jun Zhao, Zhihao Zhang, Luhui Gao, Qi Zhang, Tao Gui, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: zhao2024llama
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.01055'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods']
---
In recent times, substantial advancements have been witnessed in large
language models (LLMs), exemplified by ChatGPT, showcasing remarkable
proficiency across a range of complex tasks. However, many mainstream LLMs
(e.g. LLaMA) are pretrained on English-dominant corpus, which limits their
performance in other non-English languages. In this paper, we focus on how to
effectively transfer the capabilities of language generation and following
instructions to a non-English language. To answer this question, we conduct an
extensive empirical investigation based on LLaMA, accumulating over 1440 GPU
hours. We analyze the impact of key factors such as vocabulary extension,
further pretraining, and instruction tuning on transfer. To accurately assess
the model's level of knowledge, we employ four widely used standardized testing
benchmarks: C-Eval, MMLU, AGI-Eval, and GAOKAO-Bench. Furthermore, a
comprehensive evaluation of the model's response quality is conducted,
considering aspects such as accuracy, fluency, informativeness, logical
coherence, and harmlessness, based on LLM-Eval, a benchmarks consisting
instruction tasks from 17 diverse categories. Our evaluation results
demonstrate that comparable performance to state-of-the-art transfer models can
be achieved with less than 1% of the pretraining data, both in terms of
knowledge alignment and response quality. Furthermore, the experimental
outcomes across the thirteen low-resource languages also exhibit similar
trends. We anticipate that the conclusions revealed by the experiments will aid
the community in developing non-English LLMs.
