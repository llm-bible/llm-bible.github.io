---
layout: publication
title: 'Healthq: Unveiling Questioning Capabilities Of LLM Chains In Healthcare Conversations'
authors: Ziyu Wang, Hao Li, Di Huang, Hye-sung Kim, Chae-won Shin, Amir M. Rahmani
conference: "Arxiv"
year: 2024
bibkey: wang2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19487"}
tags: ['Security', 'Model Architecture', 'Tools', 'RAG', 'GPT']
---
Effective patient care in digital healthcare requires large language models
(LLMs) that not only answer questions but also actively gather critical
information through well-crafted inquiries. This paper introduces HealthQ, a
novel framework for evaluating the questioning capabilities of LLM healthcare
chains. By implementing advanced LLM chains, including Retrieval-Augmented
Generation (RAG), Chain of Thought (CoT), and reflective chains, HealthQ
assesses how effectively these chains elicit comprehensive and relevant patient
information. To achieve this, we integrate an LLM judge to evaluate generated
questions across metrics such as specificity, relevance, and usefulness, while
aligning these evaluations with traditional Natural Language Processing (NLP)
metrics like ROUGE and Named Entity Recognition (NER)-based set comparisons. We
validate HealthQ using two custom datasets constructed from public medical
datasets, ChatDoctor and MTS-Dialog, and demonstrate its robustness across
multiple LLM judge models, including GPT-3.5, GPT-4, and Claude. Our
contributions are threefold: we present the first systematic framework for
assessing questioning capabilities in healthcare conversations, establish a
model-agnostic evaluation methodology, and provide empirical evidence linking
high-quality questions to improved patient information elicitation.
