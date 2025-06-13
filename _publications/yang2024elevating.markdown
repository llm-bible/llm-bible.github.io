---
layout: publication
title: 'Curiousllm: Elevating Multi-document Question Answering With Llm-enhanced Knowledge Graph Reasoning'
authors: Zukang Yang, Zixuan Zhu, Xuan Zhu
conference: "Arxiv"
year: 2024
bibkey: yang2024elevating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09077"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Large Language Models (LLMs) have achieved significant success in open-domain
question answering. However, they continue to face challenges such as
hallucinations and knowledge cutoffs. These issues can be mitigated through
in-context learning by providing LLMs with relevant context before generating
answers. Recent literature proposes Knowledge Graph Prompting (KGP) which
integrates knowledge graphs with an LLM-based traversal agent to substantially
enhance document retrieval quality. However, KGP requires costly fine-tuning
with large datasets and remains prone to hallucination. In this paper, we
propose CuriousLLM, an enhancement that integrates a curiosity-driven reasoning
mechanism into an LLM agent. This mechanism enables the agent to generate
relevant follow-up questions, thereby guiding the information retrieval process
more efficiently. Central to our approach is the development of the new
Follow-upQA dataset, which includes questions and supporting evidence as input,
with follow-up questions serving as ground truths. These follow-up questions
either inquire about what is still missing to fully answer the user's query or
use special tokens to signify that the retrieved evidence is sufficient. Our
experiments show that CuriousLLM significantly boosts LLM performance in
multi-document question answering (MD-QA), circumventing the substantial
computational costs and latency from the original KGP framework.
