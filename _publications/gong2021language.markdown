---
layout: publication
title: LAWDR Language45;agnostic Weighted Document Representations From Pre45;trained Models
authors: Gong Hongyu, Chaudhary Vishrav, Tang Yuqing, Guzmán Francisco
conference: "Arxiv"
year: 2021
bibkey: gong2021language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.03379"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'RAG']
---
Cross45;lingual document representations enable language understanding in multilingual contexts and allow transfer learning from high45;resource to low45;resource languages at the document level. Recently large pre45;trained language models such as BERT XLM and XLM45;RoBERTa have achieved great success when fine45;tuned on sentence45;level downstream tasks. It is tempting to apply these cross45;lingual models to document representation learning. However there are two challenges (1) these models impose high costs on long document processing and thus many of them have strict length limit; (2) model fine45;tuning requires extra data and computational resources which is not practical in resource45;limited settings. In this work we address these challenges by proposing unsupervised Language45;Agnostic Weighted Document Representations (LAWDR). We study the geometry of pre45;trained sentence embeddings and leverage it to derive document representations without fine45;tuning. Evaluated on cross45;lingual document alignment LAWDR demonstrates comparable performance to state45;of45;the45;art models on benchmark datasets.
