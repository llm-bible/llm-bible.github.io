---
layout: publication
title: ChatGPT as a Factual Inconsistency Evaluator for Text Summarization
authors: Luo Zheheng, Xie Qianqian, Ananiadou Sophia
conference: "Arxiv"
year: 2023
bibkey: luo2023chatgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.15621"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning']
---
The performance of text summarization has been greatly boosted by pre-trained language models. A main concern of existing methods is that most generated summaries are not factually inconsistent with their source documents. To alleviate the problem many efforts have focused on developing effective factuality evaluation metrics based on natural language inference question answering and syntactic dependency et al. However these approaches are limited by either their high computational complexity or the uncertainty introduced by multi-component pipelines resulting in only partial agreement with human judgement. Most recently large language models(LLMs) have shown excellent performance in not only text generation but also language comprehension. In this paper we particularly explore ChatGPTs ability to evaluate factual inconsistency under a zero-shot setting by examining it on both coarse-grained and fine-grained evaluation tasks including binary entailment inference summary ranking and consistency rating. Experimental results indicate that ChatGPT generally outperforms previous evaluation metrics across the three tasks indicating its great potential for factual inconsistency evaluation. However a closer inspection of ChatGPTs output reveals certain limitations including its preference for more lexically similar candidates false reasoning and inadequate understanding of instructions.
