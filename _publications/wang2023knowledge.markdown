---
layout: publication
title: Knowledge-Driven CoT Exploring Faithful Reasoning in LLMs for Knowledge-intensive Question Answering
authors: Wang Keheng, Duan Feiyu, Wang Sirui, Li Peiguang, Xian Yunsen, Yin Chuantao, Rong Wenge, Xiong Zhang
conference: "Arxiv"
year: 2023
bibkey: wang2023knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.13259"}
  - {name: "Code", url: "https://github.com/AdelWang/KD-CoT/tree/main"}
tags: ['ARXIV', 'Applications', 'Has Code', 'In Context Learning', 'Tools']
---
Equipped with Chain-of-Thought (CoT) Large language models (LLMs) have shown impressive reasoning ability in various downstream tasks. Even so suffering from hallucinations and the inability to access external knowledge LLMs often come with incorrect or unfaithful intermediate reasoning steps especially in the context of answering knowledge-intensive tasks such as KBQA. To alleviate this issue we propose a framework called Knowledge-Driven Chain-of-Thought (KD-CoT) to verify and modify reasoning traces in CoT via interaction with external knowledge and thus overcome the hallucinations and error propagation. Concretely we formulate the CoT rationale process of LLMs into a structured multi-round QA format. In each round LLMs interact with a QA system that retrieves external knowledge and produce faithful reasoning traces based on retrieved precise answers. The structured CoT reasoning of LLMs is facilitated by our developed KBQA CoT collection which serves as in-context learning demonstrations and can also be utilized as feedback augmentation to train a robust retriever. Extensive experiments on WebQSP and ComplexWebQuestion datasets demonstrate the effectiveness of proposed KD-CoT in task-solving reasoning generation which outperforms the vanilla CoT ICL with an absolute success rate of 8.0 and 5.1. Furthermore our proposed feedback-augmented retriever outperforms the state-of-the-art baselines for retrieving knowledge achieving significant improvement in Hit and recall performance. Our code and data are released on https://github.com/AdelWang/KD-CoT/tree/main.
