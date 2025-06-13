---
layout: publication
title: 'Prompting And Fine-tuning Of Small Llms For Length-controllable Telephone Call Summarization'
authors: David Thulke, Yingbo Gao, Rricha Jalota, Christian Dugast, Hermann Ney
conference: "Arxiv"
year: 2024
bibkey: thulke2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18624"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
This paper explores the rapid development of a telephone call summarization
system utilizing large language models (LLMs). Our approach involves initial
experiments with prompting existing LLMs to generate summaries of telephone
conversations, followed by the creation of a tailored synthetic training
dataset utilizing stronger frontier models. We place special focus on the
diversity of the generated data and on the ability to control the length of the
generated summaries to meet various use-case specific requirements. The
effectiveness of our method is evaluated using two state-of-the-art
LLM-as-a-judge-based evaluation techniques to ensure the quality and relevance
of the summaries. Our results show that fine-tuned Llama-2-7B-based
summarization model performs on-par with GPT-4 in terms of factual accuracy,
completeness and conciseness. Our findings demonstrate the potential for
quickly bootstrapping a practical and efficient call summarization system.
