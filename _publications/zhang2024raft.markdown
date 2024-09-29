---
layout: publication
title: RAFT Adapting Language Model to Domain Specific RAG
authors: Zhang Tianjun, Patil Shishir G., Jain Naman, Shen Sheng, Zaharia Matei, Stoica Ion, Gonzalez Joseph E.
conference: "Arxiv"
year: 2024
bibkey: zhang2024raft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10131"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Pretraining Large Language Models (LLMs) on large corpora of textual data is now a standard paradigm. When using these LLMs for many downstream applications it is common to additionally bake in new knowledge (e.g. time-critical news or private domain knowledge) into the pretrained model either through RAG-based-prompting or fine-tuning. However the optimal methodology for the model to gain such new knowledge remains an open question. In this paper we present Retrieval Augmented FineTuning (RAFT) a training recipe that improves the models ability to answer questions in a open-book in-domain settings. In RAFT given a question and a set of retrieved documents we train the model to ignore those documents that dont help in answering the question which we call distractor documents. RAFT accomplishes this by citing verbatim the right sequence from the relevant document that would help answer the question. This coupled with RAFTs chain-of-thought-style response helps improve the models ability to reason. In domain-specific RAG RAFT consistently improves the models performance across PubMed HotpotQA and Gorilla datasets presenting a post-training recipe to improve pre-trained LLMs to in-domain RAG. RAFTs code and demo are open-sourced at github.com/ShishirPatil/gorilla.
