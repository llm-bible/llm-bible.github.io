---
layout: publication
title: Ctbls: Augmenting Large Language Models With Conversational Tables
authors: Sundar Anirudh S, Heck Larry
conference: "Arxiv"
year: 2023
bibkey: sundar2023augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12024"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Optimizing accuracy and performance while eliminating hallucinations of open-domain conversational large language models (LLMs) is an open research challenge. A particularly promising direction is to augment and ground LLMs with information from structured sources. This paper introduces Conversational Tables (cTBLS) a three-step architecture to retrieve and generate dialogue responses grounded on retrieved tabular information. cTBLS uses Transformer encoder embeddings for Dense Table Retrieval and obtains up to 12537; relative improvement over the retriever in the previous state-of-the-art system on the HyrbiDialogue dataset. cTBLS then uses a shared process between encoder and decoder models to perform a coarse+fine tabular knowledge (e.g. cell) ranking combined with a GPT-3.5 LLM response generator to yield a 2x relative improvement in ROUGE scores. Finally human evaluators prefer cTBLs +8037; of the time (coherency fluency) and judge informativeness to be 4x better than the previous state-of-the-art.
