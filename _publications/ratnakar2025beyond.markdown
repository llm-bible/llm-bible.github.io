---
layout: publication
title: 'Beyond QA Pairs: Assessing Parameter-efficient Fine-tuning For Fact Embedding In Llms'
authors: Shivam Ratnakar, Abhiroop Talasila, Raghav Chamadiya, Nikhil Agarwal, Vinayak K Doifode
conference: "Workshop on Preparing Good Data for Generative AI Challenges and Approaches 2025"
year: 2025
bibkey: ratnakar2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01131"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning']
---
This paper presents an extensive examination of Parameter-Efficient
Fine-Tuning (PEFT) for embedding domain specific facts into Large Language
Models (LLMs), focusing on improving the fine-tuning process by categorizing
question-answer (QA) pairs into Factual and Conceptual classes using a
BERT-based classifier. Two distinct Llama-2 models are fine-tuned based on
these classifications and evaluated using larger models like GPT-3.5 Turbo and
Gemini. Our results indicate that models trained on conceptual datasets
outperform those trained on factual datasets. Additionally, we compare the
efficiency of two synthetic fine-tuning dataset generation techniques, D-RAG
and D-Naive, with D-Naive demonstrating superior performance. Although PEFT has
shown effectiveness, our research indicates that it may not be the most optimal
method for embedding facts into LLMs. However, it has demonstrated exceptional
performance in instruction-based tasks. Our findings are reinforced by a
1000-sample dataset in the data center domain, where the fine-tuned Llama-2 7B
model significantly outperforms the baseline model in generating product
recommendations. Our study highlights the importance of QA pair categorization
and synthetic dataset generation techniques in enhancing the performance of
LLMs in specific domains.
