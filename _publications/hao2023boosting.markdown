---
layout: publication
title: "Boosting Large Language Model For Speech Synthesis: An Empirical Study"
authors: Hao Hongkun, Zhou Long, Liu Shujie, Li Jinyu, Hu Shujie, Wang Rui, Wei Furu
conference: "Arxiv"
year: 2023
bibkey: hao2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00246"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG']
---
Large language models (LLMs) have made significant advancements in natural language processing and are concurrently extending the language ability to other modalities such as speech and vision. Nevertheless most of the previous work focuses on prompting LLMs with perception abilities like auditory comprehension and the effective approach for augmenting LLMs with speech synthesis capabilities remains ambiguous. In this paper we conduct a comprehensive empirical exploration of boosting LLMs with the ability to generate speech by combining pre-trained LLM LLaMA/OPT and text-to-speech synthesis model VALL-E. We compare three integration methods between LLMs and speech synthesis models including directly fine-tuned LLMs superposed layers of LLMs and VALL-E and coupled LLMs and VALL-E using LLMs as a powerful text encoder. Experimental results show that using LoRA method to fine-tune LLMs directly to boost the speech synthesis capability does not work well and superposed LLMs and VALL-E can improve the quality of generated speech both in speaker similarity and word error rate (WER). Among these three methods coupled methods leveraging LLMs as the text encoder can achieve the best performance making it outperform original speech synthesis models with a consistently better speaker similarity and a significant (10.937;) WER reduction.
