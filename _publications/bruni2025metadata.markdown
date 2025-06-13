---
layout: publication
title: 'AMAQA: A Metadata-based QA Dataset For RAG Systems'
authors: Davide Bruni, Marco Avvenuti, Nicola Tonellotto, Maurizio Tesconi
conference: "Arxiv"
year: 2025
bibkey: bruni2025metadata
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13557"}
tags: ['RAG', 'Tools', 'Security']
---
Retrieval-augmented generation (RAG) systems are widely used in question-answering (QA) tasks, but current benchmarks lack metadata integration, hindering evaluation in scenarios requiring both textual data and external information. To address this, we present AMAQA, a new open-access QA dataset designed to evaluate tasks combining text and metadata. The integration of metadata is especially important in fields that require rapid analysis of large volumes of data, such as cybersecurity and intelligence, where timely access to relevant information is critical. AMAQA includes about 1.1 million English messages collected from 26 public Telegram groups, enriched with metadata such as timestamps, topics, emotional tones, and toxicity indicators, which enable precise and contextualized queries by filtering documents based on specific criteria. It also includes 450 high-quality QA pairs, making it a valuable resource for advancing research on metadata-driven QA and RAG systems. To the best of our knowledge, AMAQA is the first single-hop QA benchmark to incorporate metadata and labels such as topics covered in the messages. We conduct extensive tests on the benchmark, establishing a new standard for future research. We show that leveraging metadata boosts accuracy from 0.12 to 0.61, highlighting the value of structured context. Building on this, we explore several strategies to refine the LLM input by iterating over provided context and enriching it with noisy documents, achieving a further 3-point gain over the best baseline and a 14-point improvement over simple metadata filtering. The dataset is available at https://anonymous.4open.science/r/AMAQA-5D0D/
