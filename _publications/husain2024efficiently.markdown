---
layout: publication
title: Romansetu\: Efficiently Unlocking Multilingual Capabilities Of Large Language Models Via Romanization
authors: Husain Jaavid Aktar, Dabre Raj, Kumar Aswanth, Gala Jay, Jayakumar Thanmay, Puduppully Ratish, Kunchukuttan Anoop
conference: "Arxiv"
year: 2024
bibkey: husain2024efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14280"}
  - {name: "Code", url: "https://github.com/AI4Bharat/romansetu"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
This study addresses the challenge of extending Large Language Models (LLMs) to non-English languages that use non-Roman scripts. We propose an approach that utilizes the romanized form of text as an interface for LLMs hypothesizing that its frequent informal use and shared tokens with English enhance cross-lingual alignment. Our approach involves the continual pretraining of an English LLM like Llama 2 on romanized text of non-English non-Roman script languages followed by instruction tuning on romanized data. The results indicate that romanized text not only reduces token fertility by 2x-4x but also matches or outperforms native script representation across various NLU NLG and MT tasks. Moreover the embeddings computed on romanized text exhibit closer alignment with their English translations than those from the native script. Our approach presents a promising direction for leveraging the power of English LLMs in languages traditionally underrepresented in NLP. Our code is available on https://github.com/AI4Bharat/romansetu."
