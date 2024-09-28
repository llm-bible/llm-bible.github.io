---
layout: publication
title: DIVKNOWQA Assessing the Reasoning Ability of LLMs via Open-Domain Question Answering over Knowledge Base and Text
authors: Zhao Wenting, Liu Ye, Niu Tong, Wan Yao, Yu Philip S., Joty Shafiq, Zhou Yingbo, Yavuz Semih
conference: "Arxiv"
year: 2023
bibkey: zhao2023divknowqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20170"}
tags: ['ARXIV', 'Applications', 'Prompt', 'Tools']
---
Large Language Models (LLMs) have exhibited impressive generation capabilities but they suffer from hallucinations when solely relying on their internal knowledge especially when answering questions that require less commonly known information. Retrieval-augmented LLMs have emerged as a potential solution to ground LLMs in external knowledge. Nonetheless recent approaches have primarily emphasized retrieval from unstructured text corpora owing to its seamless integration into prompts. When using structured data such as knowledge graphs most methods simplify it into natural text neglecting the underlying structures. Moreover a significant gap in the current landscape is the absence of a realistic benchmark for evaluating the effectiveness of grounding LLMs on heterogeneous knowledge sources (e.g. knowledge base and text). To fill this gap we have curated a comprehensive dataset that poses two unique challenges (1) Two-hop multi-source questions that require retrieving information from both open-domain structured and unstructured knowledge sources; retrieving information from structured knowledge sources is a critical component in correctly answering the questions. (2) The generation of symbolic queries (e.g. SPARQL for Wikidata) is a key requirement which adds another layer of challenge. Our dataset is created using a combination of automatic generation through predefined reasoning chains and human annotation. We also introduce a novel approach that leverages multiple retrieval tools including text passage retrieval and symbolic language-assisted retrieval. Our model outperforms previous approaches by a significant margin demonstrating its effectiveness in addressing the above-mentioned reasoning challenges.
