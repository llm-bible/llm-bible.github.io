---
layout: publication
title: 'Closing The Gap Between Open-source And Commercial Large Language Models For Medical Evidence Summarization'
authors: Gongbo Zhang, Qiao Jin, Yiliang Zhou, Song Wang, Betina R. Idnay, Yiming Luo, Elizabeth Park, Jordan G. Nestor, Matthew E. Spotnitz, Ali Soroush, Thomas Campion, Zhiyong Lu, Chunhua Weng, Yifan Peng
conference: "Arxiv"
year: 2024
bibkey: zhang2024closing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.00588'}
tags: ['Training Techniques', 'Model Architecture', 'Applications', 'Fine-Tuning', 'GPT', 'Ethics and Bias', 'Interpretability', 'Pretraining Methods']
---
Large language models (LLMs) hold great promise in summarizing medical
evidence. Most recent studies focus on the application of proprietary LLMs.
Using proprietary LLMs introduces multiple risk factors, including a lack of
transparency and vendor dependency. While open-source LLMs allow better
transparency and customization, their performance falls short compared to
proprietary ones. In this study, we investigated to what extent fine-tuning
open-source LLMs can further improve their performance in summarizing medical
evidence. Utilizing a benchmark dataset, MedReview, consisting of 8,161 pairs
of systematic reviews and summaries, we fine-tuned three broadly-used,
open-sourced LLMs, namely PRIMERA, LongT5, and Llama-2. Overall, the fine-tuned
LLMs obtained an increase of 9.89 in ROUGE-L (95% confidence interval:
8.94-10.81), 13.21 in METEOR score (95% confidence interval: 12.05-14.37), and
15.82 in CHRF score (95% confidence interval: 13.89-16.44). The performance of
fine-tuned LongT5 is close to GPT-3.5 with zero-shot settings. Furthermore,
smaller fine-tuned models sometimes even demonstrated superior performance
compared to larger zero-shot models. The above trends of improvement were also
manifested in both human and GPT4-simulated evaluations. Our results can be
applied to guide model selection for tasks demanding particular domain
knowledge, such as medical evidence summarization.
