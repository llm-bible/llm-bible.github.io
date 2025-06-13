---
layout: publication
title: 'Leveraging Unstructured Text Data For Federated Instruction Tuning Of Large Language Models'
authors: Rui Ye, Rui Ge, Yuchi Fengting, Jingyi Chai, Yanfeng Wang, Siheng Chen
conference: "Arxiv"
year: 2024
bibkey: ye2024leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.07136'}
tags: ['Few-Shot', 'RAG', 'Tools', 'Fine-Tuning', 'Prompting']
---
Federated instruction tuning enables multiple clients to collaboratively
fine-tune a shared large language model (LLM) that can follow humans'
instructions without directly sharing raw data. However, existing literature
impractically requires that all the clients readily hold instruction-tuning
data (i.e., structured instruction-response pairs), which necessitates massive
human annotations since clients' data is usually unstructured text instead.
Addressing this, we propose a novel and flexible framework FedIT-U2S, which can
automatically transform unstructured corpus into structured data for federated
instruction tuning. FedIT-U2S consists two key steps: (1) few-shot
instruction-tuning data generation, where each unstructured data piece together
with several examples is combined to prompt an LLM in generating an
instruction-response pair. To further enhance the flexibility, a
retrieval-based example selection technique is proposed, where the examples are
automatically selected based on the relatedness between the client's data piece
and example pool, bypassing the need of determining examples in advance. (2) A
typical federated instruction tuning process based on the generated data.
Overall, FedIT-U2S can be applied to diverse scenarios as long as the client
holds valuable text corpus, broadening the application scope of federated
instruction tuning. We conduct a series of experiments on three domains
(medicine, knowledge, and math), showing that our proposed FedIT-U2S can
consistently and significantly brings improvement over the base LLM.
