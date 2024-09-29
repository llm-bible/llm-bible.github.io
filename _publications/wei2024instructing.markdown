---
layout: publication
title: Instructrag Instructing Retrieval45;augmented Generation Via Self45;synthesized Rationales
authors: Wei Zhepei, Chen Wei-lin, Meng Yu
conference: "Arxiv"
year: 2024
bibkey: wei2024instructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13629"}
tags: ['RAG', 'Training Techniques']
---
Retrieval45;augmented generation (RAG) has shown promising potential to enhance the accuracy and factuality of language models (LMs). However imperfect retrievers or noisy corpora can introduce misleading or even erroneous information to the retrieved contents posing a significant challenge to the generation quality. Existing RAG methods typically address this challenge by directly predicting final answers despite potentially noisy inputs resulting in an implicit denoising process that is difficult to interpret and verify. On the other hand the acquisition of explicit denoising supervision is often costly involving significant human efforts. In this work we propose InstructRAG where LMs explicitly learn the denoising process through self45;synthesized rationales 45;45; First we instruct the LM to explain how the ground45;truth answer is derived from retrieved documents. Then these rationales can be used either as demonstrations for in45;context learning of explicit denoising or as supervised fine45;tuning data to train the model. Compared to standard RAG approaches InstructRAG requires no additional supervision allows for easier verification of the predicted answers and effectively improves generation accuracy. Experiments show InstructRAG consistently outperforms existing RAG methods in both training45;free and trainable scenarios achieving a relative improvement of 8.337; over the best baseline method on average across five knowledge45;intensive benchmarks. Extensive analysis indicates that InstructRAG scales well with increased numbers of retrieved documents and consistently exhibits robust denoising ability even in out45;of45;domain datasets demonstrating strong generalizability.
