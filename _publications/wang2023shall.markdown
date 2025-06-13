---
layout: publication
title: 'Shall We Pretrain Autoregressive Language Models With Retrieval? A Comprehensive Study'
authors: Boxin Wang, Wei Ping, Peng Xu, Lawrence Mcafee, Zihan Liu, Mohammad Shoeybi, Yi Dong, Oleksii Kuchaiev, Bo Li, Chaowei Xiao, Anima Anandkumar, Bryan Catanzaro
conference: "Arxiv"
year: 2023
bibkey: wang2023shall
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2304.06762'}
  - {name: "Code", url: 'https://github.com/NVIDIA/Megatron-LM/blob/main/tools/retro/README.md'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'GPT', 'Applications', 'Survey Paper', 'Pretraining Methods']
---
Large decoder-only language models (LMs) can be largely improved in terms of
perplexity by retrieval (e.g., RETRO), but its impact on text generation
quality and downstream task accuracy is unclear. Thus, it is still an open
question: shall we pretrain large autoregressive LMs with retrieval? To answer
it, we perform a comprehensive study on a scalable pre-trained
retrieval-augmented LM (i.e., RETRO) compared with standard GPT and
retrieval-augmented GPT incorporated at fine-tuning or inference stages. We
first provide the recipe to reproduce RETRO up to 9.5B parameters while
retrieving a text corpus with 330B tokens. Based on that, we have the following
novel findings: i) RETRO outperforms GPT on text generation with much less
degeneration (i.e., repetition), moderately higher factual accuracy, and
slightly lower toxicity with a nontoxic retrieval database. ii) On the LM
Evaluation Harness benchmark, RETRO largely outperforms GPT on
knowledge-intensive tasks, but is on par with GPT on other tasks. Furthermore,
we introduce a simple variant of the model, RETRO++, which largely improves
open-domain QA results of original RETRO (e.g., EM score +8.6 on Natural
Question) and significantly outperforms retrieval-augmented GPT in both
fine-tuning and zero-shot evaluation settings. Our findings highlight the
promising direction of pretraining autoregressive LMs with retrieval as future
foundation models. We release our code and model at:
https://github.com/NVIDIA/Megatron-LM/blob/main/tools/retro/README.md
