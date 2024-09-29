---
layout: publication
title: 'Imagination Augmented Generation: Learning To Imagine Richer Context For Question Answering Over Large Language Models'
authors: Liao Huanxuan, He Shizhu, Xu Yao, Zhang Yuanzhe, Liu Kang, Liu Shengping, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: liao2024imagination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15268"}
  - {name: "Code", url: "https://github.com/Xnhyacinth/IAG"}
tags: ['Applications', 'Has Code', 'RAG', 'Tools']
---
Retrieval-Augmented-Generation and Gener-ation-Augmented-Generation have been proposed to enhance the knowledge required for question answering over Large Language Models (LLMs). However the former relies on external resources and both require incorporating explicit documents into the context which increases execution costs and susceptibility to noise data. Recent works indicate that LLMs have modeled rich knowledge albeit not effectively triggered or awakened. Inspired by this we propose a novel knowledge-augmented framework Imagination-Augmented-Generation (IAG) which simulates the human capacity to compensate for knowledge deficits while answering questions solely through imagination thereby awakening relevant knowledge in LLMs without relying on external resources. Guided by IAG we propose an imagine richer context method for question answering (IMcQA). IMcQA consists of two modules explicit imagination which generates a short dummy document by learning from long context compression and implicit imagination which creates flexible adapters by distilling from a teacher model with a long context. Experimental results on three datasets demonstrate that IMcQA exhibits significant advantages in both open-domain and closed-book settings as well as in out-of-distribution generalization. Our code will be available at https://github.com/Xnhyacinth/IAG."
