---
layout: publication
title: 'Addressing Hallucinations In Language Models With Knowledge Graph Embeddings As An Additional Modality'
authors: Viktoriia Chekalina, Anton Razzhigaev, Elizaveta Goncharova, Andrey Kuznetsov
conference: "Arxiv"
year: 2024
bibkey: chekalina2024addressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.11531"}
tags: ['Pretraining Methods', 'Training Techniques', 'Applications', 'Fine-Tuning']
---
In this paper we present an approach to reduce hallucinations in Large
Language Models (LLMs) by incorporating Knowledge Graphs (KGs) as an additional
modality. Our method involves transforming input text into a set of KG
embeddings and using an adapter to integrate these embeddings into the language
model space, without relying on external retrieval processes.
  To facilitate this, we created WikiEntities, a dataset containing over 3
million Wikipedia texts annotated with entities from Wikidata and their
corresponding embeddings from PyTorch-BigGraph. This dataset serves as a
valuable resource for training Entity Linking models and adapting the described
method to various LLMs using specialized adapters.
  Our method does not require fine-tuning of the language models themselves;
instead, we only train the adapter. This ensures that the model's performance
on other tasks is not affected. We trained an adapter for the Mistral 7B, LLaMA
2-7B (chat), and LLaMA 3-8B (instruct) models using this dataset and
demonstrated that our approach improves performance on the HaluEval, True-False
benchmarks and FEVER dataset. The results indicate that incorporating KGs as a
new modality can effectively reduce hallucinations and improve the factual
accuracy of language models, all without the need for external retrieval.
