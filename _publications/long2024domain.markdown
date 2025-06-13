---
layout: publication
title: 'Bailicai: A Domain-optimized Retrieval-augmented Generation Framework For Medical Applications'
authors: Cui Long, Yongbin Liu, Chunping Ouyang, Ying Yu
conference: "Arxiv"
year: 2024
bibkey: long2024domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21055"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have exhibited remarkable proficiency in natural
language understanding, prompting extensive exploration of their potential
applications across diverse domains. In the medical domain, open-source LLMs
have demonstrated moderate efficacy following domain-specific fine-tuning;
however, they remain substantially inferior to proprietary models such as GPT-4
and GPT-3.5. These open-source models encounter limitations in the
comprehensiveness of domain-specific knowledge and exhibit a propensity for
'hallucinations' during text generation. To mitigate these issues, researchers
have implemented the Retrieval-Augmented Generation (RAG) approach, which
augments LLMs with background information from external knowledge bases while
preserving the model's internal parameters. However, document noise can
adversely affect performance, and the application of RAG in the medical field
remains in its nascent stages. This study presents the Bailicai framework: a
novel integration of retrieval-augmented generation with large language models
optimized for the medical domain. The Bailicai framework augments the
performance of LLMs in medicine through the implementation of four sub-modules.
Experimental results demonstrate that the Bailicai approach surpasses existing
medical domain LLMs across multiple medical benchmarks and exceeds the
performance of GPT-3.5. Furthermore, the Bailicai method effectively attenuates
the prevalent issue of hallucinations in medical applications of LLMs and
ameliorates the noise-related challenges associated with traditional RAG
techniques when processing irrelevant or pseudo-relevant documents.
