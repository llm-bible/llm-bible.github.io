---
layout: publication
title: 'MEG: Medical Knowledge-augmented Large Language Models For Question Answering'
authors: Laura Cabello, Carmen Martin-turrero, Uchenna Akujuobi, Anders Søgaard, Carlos Bobed
conference: "Arxiv"
year: 2024
bibkey: cabello2024medical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.03883'}
tags: ['RAG', 'Applications', 'Training Techniques']
---
Question answering is a natural language understanding task that involves
reasoning over both explicit context, and unstated relevant domain knowledge.
Despite the high cost of training, large language models (LLMs) -- the backbone
of most modern question-answering systems -- still struggle to reliably capture
the nuanced relationships between concepts that are crucial for reasoning in
specialized fields like medicine. In this work, we present MEG, a
parameter-efficient approach for medical knowledge-augmented LLMs. MEG uses a
lightweight mapping network to incorporate knowledge graph embeddings into the
LLM, enabling it to leverage external knowledge in a cost-effective way. We
evaluate our method on four popular medical multiple-choice datasets and show
that LLMs i) can effectively interpret knowledge graph embeddings and ii) gain
significant advantages from the factual grounding these embeddings provide. MEG
attains an average of +6.7% and +9.9% accuracy over specialized models like
BioMistral-7B and MediTron-7B, respectively. Finally, we show that MEG's
performance remains robust to the choice of graph encoder.
