---
layout: publication
title: 'Learning To Summarize From Llm-generated Feedback'
authors: Hwanjun Song, Taewon Yun, Yuho Lee, Jihwan Oh, Gihun Lee, Jason Cai, Hang Su
conference: "Arxiv"
year: 2024
bibkey: song2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13116"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Developing effective text summarizers remains a challenge due to issues like
hallucinations, key information omissions, and verbosity in LLM-generated
summaries. This work explores using LLM-generated feedback to improve summary
quality by aligning the summaries with human preferences for faithfulness,
completeness, and conciseness. We introduce FeedSum, a large-scale dataset
containing multi-dimensional LLM feedback on summaries of varying quality
across diverse domains. Our experiments show how feedback quality,
dimensionality, and granularity influence preference learning, revealing that
high-quality, multi-dimensional, fine-grained feedback significantly improves
summary generation. We also compare two methods for using this feedback:
supervised fine-tuning and direct preference optimization. Finally, we
introduce SummLlama3-8b, a model that outperforms the nearly 10x larger
Llama3-70b-instruct in generating human-preferred summaries, demonstrating that
smaller models can achieve superior performance with appropriate training. The
full dataset and SummLlama3-8B model are available at
https://huggingface.co/datasets/DISLab/FeedSum and
https://huggingface.co/DISLab/SummLlama3-8B.
