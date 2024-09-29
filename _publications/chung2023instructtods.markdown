---
layout: publication
title: InstructTODS Large Language Models for End-to-End Task-Oriented Dialogue Systems
authors: Chung Willy, Cahyawijaya Samuel, Wilie Bryan, Lovenia Holy, Fung Pascale
conference: "Arxiv"
year: 2023
bibkey: chung2023instructtods
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08885"}
  - {name: "Code", url: "https://github.com/WillyHC22/InstructTODS/"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have been used for diverse tasks in natural language processing (NLP) yet remain under-explored for task-oriented dialogue systems (TODS) especially for end-to-end TODS. We present InstructTODS a novel off-the-shelf framework for zero-shot end-to-end task-oriented dialogue systems that can adapt to diverse domains without fine-tuning. By leveraging LLMs InstructTODS generates a proxy belief state that seamlessly translates user intentions into dynamic queries for efficient interaction with any KB. Our extensive experiments demonstrate that InstructTODS achieves comparable performance to fully fine-tuned TODS in guiding dialogues to successful completion without prior knowledge or task-specific data. Furthermore a rigorous human evaluation of end-to-end TODS shows that InstructTODS produces dialogue responses that notably outperform both the gold responses and the state-of-the-art TODS in terms of helpfulness informativeness and humanness. Moreover the effectiveness of LLMs in TODS is further supported by our comprehensive evaluations on TODS subtasks dialogue state tracking intent classification and response generation. Code and implementations could be found here https://github.com/WillyHC22/InstructTODS/
