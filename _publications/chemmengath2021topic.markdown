---
layout: publication
title: Topic Transferable Table Question Answering
authors: Chemmengath Saneem Ahmed, Kumar Vishwajeet, Bharadwaj Samarth, Sen Jaydeep, Canim Mustafa, Chakrabarti Soumen, Gliozzo Alfio, Sankaranarayanan Karthik
conference: "Arxiv"
year: 2021
bibkey: chemmengath2021topic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.07377"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Weakly45;supervised table question45;answering(TableQA) models have achieved state45;of45;art performance by using pre45;trained BERT transformer to jointly encoding a question and a table to produce structured query for the question. However in practical settings TableQA systems are deployed over table corpora having topic and word distributions quite distinct from BERTs pretraining corpus. In this work we simulate the practical topic shift scenario by designing novel challenge benchmarks WikiSQL45;TS and WikiTQ45;TS consisting of train45;dev45;test splits in five distinct topic groups based on the popular WikiSQL and WikiTableQuestions datasets. We empirically show that despite pre45;training on large open45;domain text performance of models degrades significantly when they are evaluated on unseen topics. In response we propose T3QA (Topic Transferable Table Question Answering) a pragmatic adaptation framework for TableQA comprising of (1) topic45;specific vocabulary injection into BERT (2) a novel text45;to45;text transformer generator (such as T5 GPT2) based natural language question generation pipeline focused on generating topic specific training data and (3) a logical form reranker. We show that T3QA provides a reasonably good baseline for our topic shift benchmarks. We believe our topic split benchmarks will lead to robust TableQA solutions that are better suited for practical deployment.
