---
layout: publication
title: 'Leveraging Fine-tuned Retrieval-augmented Generation With Long-context Support: For 3GPP Standards'
authors: Omar Erak, Nouf Alabbasi, Omar Alhussein, Ismail Lotfi, Amr Hussein, Sami Muhaidat, Merouane Debbah
conference: "Arxiv"
year: 2024
bibkey: erak2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11775"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'ACL', 'Training Techniques', 'Pretraining Methods']
---
Recent studies show that large language models (LLMs) struggle with technical
standards in telecommunications. We propose a fine-tuned retrieval-augmented
generation (RAG) system based on the Phi-2 small language model (SLM) to serve
as an oracle for communication networks. Our developed system leverages
forward-looking semantic chunking to adaptively determine parsing breakpoints
based on embedding similarity, enabling effective processing of diverse
document formats. To handle the challenge of multiple similar contexts in
technical standards, we employ a re-ranking algorithm to prioritize the most
relevant retrieved chunks. Recognizing the limitations of Phi-2's small context
window, we implement a recent technique, namely SelfExtend, to expand the
context window during inference, which not only boosts the performance but also
can accommodate a wider range of user queries and design requirements from
customers to specialized technicians. For fine-tuning, we utilize the low-rank
adaptation (LoRA) technique to enhance computational efficiency during training
and enable effective fine-tuning on small datasets. Our comprehensive
experiments demonstrate substantial improvements over existing
question-answering approaches in the telecom domain, achieving performance that
exceeds larger language models such as GPT-4 (which is about 880 times larger
in size). This work presents a novel approach to leveraging SLMs for
communication networks, offering a balance of efficiency and performance. This
work can serve as a foundation towards agentic language models for networks.
