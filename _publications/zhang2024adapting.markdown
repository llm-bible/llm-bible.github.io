---
layout: publication
title: RAFT Adapting Language Model To Domain Specific RAG
authors: Zhang Tianjun, Patil Shishir G., Jain Naman, Shen Sheng, Zaharia Matei, Stoica Ion, Gonzalez Joseph E.
conference: "Arxiv"
year: 2024
bibkey: zhang2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10131"}
tags: ['Applications', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Pretraining Large Language Models (LLMs) on large corpora of textual data is now a standard paradigm. When using these LLMs for many downstream applications it is common to additionally bake in new knowledge (e.g. time45;critical news or private domain knowledge) into the pretrained model either through RAG45;based45;prompting or fine45;tuning. However the optimal methodology for the model to gain such new knowledge remains an open question. In this paper we present Retrieval Augmented FineTuning (RAFT) a training recipe that improves the models ability to answer questions in a open45;book in45;domain settings. In RAFT given a question and a set of retrieved documents we train the model to ignore those documents that dont help in answering the question which we call distractor documents. RAFT accomplishes this by citing verbatim the right sequence from the relevant document that would help answer the question. This coupled with RAFTs chain45;of45;thought45;style response helps improve the models ability to reason. In domain45;specific RAG RAFT consistently improves the models performance across PubMed HotpotQA and Gorilla datasets presenting a post45;training recipe to improve pre45;trained LLMs to in45;domain RAG. RAFTs code and demo are open45;sourced at github.com/ShishirPatil/gorilla.
