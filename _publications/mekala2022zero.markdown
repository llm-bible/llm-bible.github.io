---
layout: publication
title: "ZEROTOP: Zero-shot Task-oriented Semantic Parsing Using Large Language Models"
authors: Mekala Dheeraj, Wolfe Jason, Roy Subhro
conference: "Arxiv"
year: 2022
bibkey: mekala2022zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10815"}
tags: ['Applications', 'Prompting', 'RAG']
---
We explore the use of large language models (LLMs) for zero-shot semantic parsing. Semantic parsing involves mapping natural language utterances to task-specific meaning representations. Language models are generally trained on the publicly available text and code and cannot be expected to directly generalize to domain-specific parsing tasks in a zero-shot setting. In this work we propose ZEROTOP a zero-shot task-oriented parsing method that decomposes a semantic parsing problem into a set of abstractive and extractive question-answering (QA) problems enabling us to leverage the ability of LLMs to zero-shot answer reading comprehension questions. For each utterance we prompt the LLM with questions corresponding to its top-level intent and a set of slots and use the LLM generations to construct the target meaning representation. We observe that current LLMs fail to detect unanswerable questions; and as a result cannot handle questions corresponding to missing slots. To address this problem we fine-tune a language model on public QA datasets using synthetic negative samples. Experimental results show that our QA-based decomposition paired with the fine-tuned LLM can correctly parse ~1637; of utterances in the MTOP dataset without requiring any annotated data.
