---
layout: publication
title: 'Conceptformer: Towards Efficient Use Of Knowledge-graph Embeddings In Large Language Models'
authors: Joel Barmettler, Abraham Bernstein, Luca Rossetto
conference: "Arxiv"
year: 2025
bibkey: barmettler2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07624'}
tags: ['Attention Mechanism', 'RAG', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) has enjoyed increased attention in the
recent past and recent advancements in Large Language Models (LLMs) have
highlighted the importance of integrating world knowledge into these systems.
Current RAG methodologies often modify the internal architecture of pre-trained
language models (PLMs) or rely on textifying knowledge graphs (KGs), which is
inefficient in terms of token usage. This paper introduces ConceptFormer, a new
approach to augment LLMs with structured knowledge from KGs, such as Wikidata,
without altering their internal structure or relying on textual input of KGs.
ConceptFormer operates in the LLM embedding vector space, creating and
injecting *concept vectors* that encapsulate the information of the KG
nodes directly. Trained in conjunction with a frozen LLM, ConceptFormer
generates a comprehensive lookup table that maps KG nodes to their respective
concept vectors. The approach aims to enhance the factual recall capabilities
of LLMs by enabling them to process these concept vectors natively, thus
enriching them with structured world knowledge in an efficient and scalable
manner. Our experiments demonstrate that the addition of concept vectors to
GPT-2 0.1B substantially increases its factual recall ability (Hit@10) by up to
272% when tested on sentences from Wikipedia and up to 348% on synthetically
generated sentences. Even injecting only a single concept vector into the
prompt increases factual recall ability (Hit@10) by up to 213% on Wikipedia
sentences, significantly outperforming RAG with graph textification while
consuming 130x fewer input tokens.
