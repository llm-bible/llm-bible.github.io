---
layout: publication
title: Mitigating Fine45;grained Hallucination By Fine45;tuning Large Vision45;language Models With Caption Rewrites
authors: Lei Wang, Jiabang He, Shenshen Li, Ning Liu, Ee-peng Lim
conference: "Arxiv"
year: 2023
bibkey: wang2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2312.01701v1"}
  - {name: "Code", url: "https://github.com/Anonymousanoy/FOHE"}
tags: ['Applications', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Tools']
---
Large language models (LLMs) have shown remarkable performance in natural language processing (NLP) tasks. To comprehend and execute diverse human instructions over image data instruction45;tuned large vision45;language models (LVLMs) have been introduced. However LVLMs may suffer from different types of object hallucinations. Nevertheless LVLMs are evaluated for coarse45;grained object hallucinations only (i.e. generated objects non45;existent in the input image). The fine45;grained object attributes and behaviors non45;existent in the image may still be generated but not measured by the current evaluation methods. In this paper we thus focus on reducing fine45;grained hallucinations of LVLMs. We propose textit123;ReCaption125; a framework that consists of two components rewriting captions using ChatGPT and fine45;tuning the instruction45;tuned LVLMs on the rewritten captions. We also propose a fine45;grained probing45;based evaluation method named textit123;Fine45;Grained Object Hallucination Evaluation125; (textit123;FGHE125;). Our experiment results demonstrate that ReCaption effectively reduces fine45;grained object hallucination for different LVLM options and improves their text generation quality. The code can be found at https://github.com/Anonymousanoy/FOHE.
