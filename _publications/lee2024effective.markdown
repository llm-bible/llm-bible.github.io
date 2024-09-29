---
layout: publication
title: "Effective And Efficient Conversation Retrieval For Dialogue State Tracking With Implicit Text Summaries"
authors: Lee Seanie, Cheng Jianpeng, Driesen Joris, Coca Alexandru, Johannsen Anders
conference: "Arxiv"
year: 2024
bibkey: lee2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13043"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Few-shot dialogue state tracking (DST) with Large Language Models (LLM) relies on an effective and efficient conversation retriever to find similar in-context examples for prompt learning. Previous works use raw dialogue context as search keys and queries and a retriever is fine-tuned with annotated dialogues to achieve superior performance. However the approach is less suited for scaling to new domains or new annotation languages where fine-tuning data is unavailable. To address this problem we handle the task of conversation retrieval based on text summaries of the conversations. A LLM-based conversation summarizer is adopted for query and key generation which enables effective maximum inner product search. To avoid the extra inference cost brought by LLM-based conversation summarization we further distill a light-weight conversation encoder which produces query embeddings without decoding summaries for test conversations. We validate our retrieval approach on MultiWOZ datasets with GPT-Neo-2.7B and LLaMA-7B/30B. The experimental results show a significant improvement over relevant baselines in real few-shot DST settings.
