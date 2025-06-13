---
layout: publication
title: 'LEAF: Learning And Evaluation Augmented By Fact-checking To Improve Factualness In Large Language Models'
authors: Hieu Tran, Junda Wang, Yujan Ting, Weijing Huang, Terrence Chen
conference: "Arxiv"
year: 2024
bibkey: tran2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23526"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large language models (LLMs) have shown remarkable capabilities in various
natural language processing tasks, yet they often struggle with maintaining
factual accuracy, particularly in knowledge-intensive domains like healthcare.
This study introduces LEAF: Learning and Evaluation Augmented by Fact-Checking,
a novel approach designed to enhance the factual reliability of LLMs, with a
focus on medical question answering (QA). LEAF utilizes a dual strategy to
enhance the factual accuracy of responses from models such as Llama 3 70B
Instruct and Llama 3 8B Instruct. The first strategy, Fact-Check-Then-RAG,
improves Retrieval-Augmented Generation (RAG) by incorporating fact-checking
results to guide the retrieval process without updating model parameters. The
second strategy, Learning from Fact-Checks via Self-Training, involves
supervised fine-tuning (SFT) on fact-checked responses or applying Simple
Preference Optimization (SimPO) with fact-checking as a ranking mechanism, both
updating LLM parameters from supervision. These findings suggest that
integrating fact-checked responses whether through RAG enhancement or
self-training enhances the reliability and factual correctness of LLM outputs,
offering a promising solution for applications where information accuracy is
crucial.
