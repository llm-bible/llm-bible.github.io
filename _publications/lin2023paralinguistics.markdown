---
layout: publication
title: 'Paralinguistics-enhanced Large Language Modeling Of Spoken Dialogue'
authors: Lin Guan-ting, Shivakumar Prashanth Gurunath, Gandhe Ankur, Yang Chao-han Huck, Gu Yile, Ghosh Shalini, Stolcke Andreas, Lee Hung-yi, Bulyko Ivan
conference: "Arxiv"
year: 2023
bibkey: lin2023paralinguistics
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15316"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Transformer']
---
Large Language Models (LLMs) have demonstrated superior abilities in tasks such as chatting reasoning and question-answering. However standard LLMs may ignore crucial paralinguistic information such as sentiment emotion and speaking style which are essential for achieving natural human-like spoken conversation especially when such information is conveyed by acoustic cues. We therefore propose Paralinguistics-enhanced Generative Pretrained Transformer (ParalinGPT) an LLM that utilizes text and speech modalities to better model the linguistic content and paralinguistic attributes of spoken dialogue. The model takes the conversational context of text speech embeddings and paralinguistic attributes as input prompts within a serialized multitasking multimodal framework. Specifically our framework serializes tasks in the order of current paralinguistic attribute prediction response paralinguistic attribute prediction and response text generation with autoregressive conditioning. We utilize the Switchboard-1 corpus including its sentiment labels as the paralinguistic attribute as our spoken dialogue dataset. Experimental results indicate the proposed serialized multitasking method outperforms typical sequence classification techniques on current and response sentiment classification. Furthermore leveraging conversational context and speech embeddings significantly improves both response text generation and sentiment prediction. Our proposed framework achieves relative improvements of 6.737; 12.037; and 3.537; in current sentiment accuracy response sentiment accuracy and response text BLEU score respectively.
