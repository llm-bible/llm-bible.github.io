---
layout: publication
title: Multi-Lingual Malaysian Embedding Leveraging Large Language Models for Semantic Representations
authors: Zolkepli Husein, Razak Aisyah, Adha Kamarul, Nazhan Ariff
conference: "Arxiv"
year: 2024
bibkey: zolkepli2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03053"}
tags: ['Fine Tuning', 'RAG']
---
In this work we present a comprehensive exploration of finetuning Malaysian language models specifically Llama2 and Mistral on embedding tasks involving negative and positive pairs. We release two distinct models tailored for Semantic Similarity and Retrieval-Augmented Generation (RAG). For Semantic Similarity our 600 million parameter Llama2 model outperforms OpenAI text-embedding-ada-002 across all recall@k metrics for b.cari.com.my c.cari.com.my Malay news and Malaysian Twitter test sets. In the realm of RAG models our approach proves competitive with OpenAI text-embedding-ada-002 in the Malaysian context. Notably our 2 billion parameter Llama2 model achieves superior Recall@5 Recall@10 for the Melayu keyword research papers dataset and excels in Recall@3 Recall@5 and Recall@10 for the lom.agc.gov.my dataset. These findings underscore the effectiveness of our finetuning strategy and highlight the performance gains in both Semantic Similarity and RAG tasks. All models released at https://huggingface.co/collections/mesolitica/malaysian-embedding-6523612bfe5881ad35f81b99
