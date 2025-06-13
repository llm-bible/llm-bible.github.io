---
layout: publication
title: 'Paralinguistics-enhanced Large Language Modeling Of Spoken Dialogue'
authors: Guan-ting Lin, Prashanth Gurunath Shivakumar, Ankur Gandhe, Chao-han Huck Yang, Yile Gu, Shalini Ghosh, Andreas Stolcke, Hung-yi Lee, Ivan Bulyko
conference: "Arxiv"
year: 2023
bibkey: lin2023paralinguistics
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.15316'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Applications', 'Multimodal Models', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated superior abilities in tasks
such as chatting, reasoning, and question-answering. However, standard LLMs may
ignore crucial paralinguistic information, such as sentiment, emotion, and
speaking style, which are essential for achieving natural, human-like spoken
conversation, especially when such information is conveyed by acoustic cues. We
therefore propose Paralinguistics-enhanced Generative Pretrained Transformer
(ParalinGPT), an LLM that utilizes text and speech modalities to better model
the linguistic content and paralinguistic attributes of spoken dialogue. The
model takes the conversational context of text, speech embeddings, and
paralinguistic attributes as input prompts within a serialized multitasking
multimodal framework. Specifically, our framework serializes tasks in the order
of current paralinguistic attribute prediction, response paralinguistic
attribute prediction, and response text generation with autoregressive
conditioning. We utilize the Switchboard-1 corpus, including its sentiment
labels as the paralinguistic attribute, as our spoken dialogue dataset.
Experimental results indicate the proposed serialized multitasking method
outperforms typical sequence classification techniques on current and response
sentiment classification. Furthermore, leveraging conversational context and
speech embeddings significantly improves both response text generation and
sentiment prediction. Our proposed framework achieves relative improvements of
6.7%, 12.0%, and 3.5% in current sentiment accuracy, response sentiment
accuracy, and response text BLEU score, respectively.
