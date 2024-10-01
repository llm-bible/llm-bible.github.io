---
layout: publication
title: 'Code-style In-context Learning For Knowledge-based Question Answering'
authors: Nie Zhijie, Zhang Richong, Wang Zhongyuan, Liu Xudong
conference: "Arxiv"
year: 2023
bibkey: nie2023code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04695"}
  - {name: "Code", url: "https://github.com/Arthurizijar/KB-Coder"}
tags: ['Applications', 'Few Shot', 'Has Code', 'In Context Learning', 'Prompting', 'Tools', 'Training Techniques']
---
"Current methods for Knowledge-Based Question Answering (KBQA) usually rely on complex training techniques and model frameworks, leading to many limitations in practical applications. Recently, the emergence of In-Context Learning (ICL) capabilities in Large Language Models (LLMs) provides a simple and training-free semantic parsing paradigm for KBQA: Given a small number of questions and their labeled logical forms as demo examples, LLMs can understand the task intent and generate the logic form for a new question. However, current powerful LLMs have little exposure to logic forms during pre-training, resulting in a high format error rate. To solve this problem, we propose a code-style in-context learning method for KBQA, which converts the generation process of unfamiliar logical form into the more familiar code generation process for LLMs. Experimental results on three mainstream datasets show that our method dramatically mitigated the formatting error problem in generating logic forms while realizing a new SOTA on WebQSP, GrailQA, and GraphQ under the few-shot setting. The code and supplementary files are released at https://github.com/Arthurizijar/KB-Coder ."
