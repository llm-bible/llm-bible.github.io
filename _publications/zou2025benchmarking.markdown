---
layout: publication
title: 'Benchmarking Next-generation Reasoning-focused Large Language Models In Ophthalmology: A Head-to-head Evaluation On 5,888 Items'
authors: Minjie Zou, Sahana Srinivasan, Thaddaeus Wai Soon Lo, Ke Zou, Gabriel Dawei Yang, Xuguang Ai, Hyunjae Kim, Maxwell Singer, Fares Antaki, Kelvin Li, Robert Chang, Marcus Tan, David Ziyou Chen, Dianbo Liu, Qingyu Chen, Yih Chung Tham
conference: "Arxiv"
year: 2025
bibkey: zou2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11186"}
tags: ['BERT', 'RAG', 'Model Architecture']
---
Recent advances in reasoning-focused large language models (LLMs) mark a
shift from general LLMs toward models designed for complex decision-making, a
crucial aspect in medicine. However, their performance in specialized domains
like ophthalmology remains underexplored. This study comprehensively evaluated
and compared the accuracy and reasoning capabilities of four newly developed
reasoning-focused LLMs, namely DeepSeek-R1, OpenAI o1, o3-mini, and Gemini 2.0
Flash-Thinking. Each model was assessed using 5,888 multiple-choice
ophthalmology exam questions from the MedMCQA dataset in zero-shot setting.
Quantitative evaluation included accuracy, Macro-F1, and five text-generation
metrics (ROUGE-L, METEOR, BERTScore, BARTScore, and AlignScore), computed
against ground-truth reasonings. Average inference time was recorded for a
subset of 100 randomly selected questions. Additionally, two board-certified
ophthalmologists qualitatively assessed clarity, completeness, and reasoning
structure of responses to differential diagnosis questions.O1 (0.902) and
DeepSeek-R1 (0.888) achieved the highest accuracy, with o1 also leading in
Macro-F1 (0.900). The performance of models across the text-generation metrics
varied: O3-mini excelled in ROUGE-L (0.151), o1 in METEOR (0.232), DeepSeek-R1
and o3-mini tied for BERTScore (0.673), DeepSeek-R1 (-4.105) and Gemini 2.0
Flash-Thinking (-4.127) performed best in BARTScore, while o3-mini (0.181) and
o1 (0.176) led AlignScore. Inference time across the models varied, with
DeepSeek-R1 being slowest (40.4 seconds) and Gemini 2.0 Flash-Thinking fastest
(6.7 seconds). Qualitative evaluation revealed that DeepSeek-R1 and Gemini 2.0
Flash-Thinking tended to provide detailed and comprehensive intermediate
reasoning, whereas o1 and o3-mini displayed concise and summarized
justifications.
