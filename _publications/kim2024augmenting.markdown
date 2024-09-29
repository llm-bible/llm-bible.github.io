---
layout: publication
title: Augmenting Query And Passage For Retrieval45;augmented Generation Using Llms For Open45;domain Question Answering
authors: Kim Minsang, Park Cheoneum, Baek Seungjun
conference: "Arxiv"
year: 2024
bibkey: kim2024augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14277"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG']
---
Retrieval45;augmented generation (RAG) has received much attention for Open45;domain question45;answering (ODQA) tasks as a means to compensate for the parametric knowledge of large language models (LLMs). While previous approaches focused on processing retrieved passages to remove irrelevant context they still rely heavily on the quality of retrieved passages which can degrade if the question is ambiguous or complex. In this paper we propose a simple yet efficient method called question and passage augmentation via LLMs for open45;domain QA. Our method first decomposes the original questions into multiple45;step sub45;questions. By augmenting the original question with detailed sub45;questions and planning we are able to make the query more specific on what needs to be retrieved improving the retrieval performance. In addition to compensate for the case where the retrieved passages contain distracting information or divided opinions we augment the retrieved passages with self45;generated passages by LLMs to guide the answer extraction. Experimental results show that the proposed scheme outperforms the previous state45;of45;the45;art and achieves significant performance gain over existing RAG methods.
