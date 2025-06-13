---
layout: publication
title: 'Can Open-source Llms Compete With Commercial Models? Exploring The Few-shot Performance Of Current GPT Models In Biomedical Tasks'
authors: Samy Ateia, Udo Kruschwitz
conference: "Arxiv"
year: 2024
bibkey: ateia2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13511"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Commercial large language models (LLMs), like OpenAI's GPT-4 powering ChatGPT
and Anthropic's Claude 3 Opus, have dominated natural language processing (NLP)
benchmarks across different domains. New competing Open-Source alternatives
like Mixtral 8x7B or Llama 3 have emerged and seem to be closing the gap while
often offering higher throughput and being less costly to use. Open-Source LLMs
can also be self-hosted, which makes them interesting for enterprise and
clinical use cases where sensitive data should not be processed by third
parties. We participated in the 12th BioASQ challenge, which is a retrieval
augmented generation (RAG) setting, and explored the performance of current GPT
models Claude 3 Opus, GPT-3.5-turbo and Mixtral 8x7b with in-context learning
(zero-shot, few-shot) and QLoRa fine-tuning. We also explored how additional
relevant knowledge from Wikipedia added to the context-window of the LLM might
improve their performance. Mixtral 8x7b was competitive in the 10-shot setting,
both with and without fine-tuning, but failed to produce usable results in the
zero-shot setting. QLoRa fine-tuning and Wikipedia context did not lead to
measurable performance gains. Our results indicate that the performance gap
between commercial and open-source models in RAG setups exists mainly in the
zero-shot setting and can be closed by simply collecting few-shot examples for
domain-specific use cases. The code needed to rerun these experiments is
available through GitHub.
