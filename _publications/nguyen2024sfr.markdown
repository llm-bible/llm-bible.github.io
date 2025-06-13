---
layout: publication
title: 'SFR-RAG: Towards Contextually Faithful Llms'
authors: Xuan-phi Nguyen, Shrey Pandit, Senthil Purushwalkam, Austin Xu, Hailin Chen, Yifei Ming, Zixuan Ke, Silvio Savarese, Caiming Xong, Shafiq Joty
conference: "Arxiv"
year: 2024
bibkey: nguyen2024sfr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09916"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture']
---
Retrieval Augmented Generation (RAG), a paradigm that integrates external
contextual information with large language models (LLMs) to enhance factual
accuracy and relevance, has emerged as a pivotal area in generative AI. The
LLMs used in RAG applications are required to faithfully and completely
comprehend the provided context and users' questions, avoid hallucination,
handle unanswerable, counterfactual or otherwise low-quality and irrelevant
contexts, perform complex multi-hop reasoning and produce reliable citations.
In this paper, we introduce SFR-RAG, a small LLM that is instruction-tuned with
an emphasis on context-grounded generation and hallucination minimization. We
also present ContextualBench, a new evaluation framework compiling multiple
popular and diverse RAG benchmarks, such as HotpotQA and TriviaQA, with
consistent RAG settings to ensure reproducibility and consistency in model
assessments. Experimental results demonstrate that our SFR-RAG-9B model
outperforms leading baselines such as Command-R+ (104B) and GPT-4o, achieving
state-of-the-art results in 3 out of 7 benchmarks in ContextualBench with
significantly fewer parameters. The model is also shown to be resilient to
alteration in the contextual information and behave appropriately when relevant
context is removed. Additionally, the SFR-RAG model maintains competitive
performance in general instruction-following tasks and function-calling
capabilities.
