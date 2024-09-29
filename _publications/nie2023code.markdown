---
layout: publication
title: Code45;style In45;context Learning For Knowledge45;based Question Answering
authors: Nie Zhijie, Zhang Richong, Wang Zhongyuan, Liu Xudong
conference: "Arxiv"
year: 2023
bibkey: nie2023code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04695"}
  - {name: "Code", url: "https://github.com/Arthurizijar/KB&#45;Coder"}
tags: ['Applications', 'Has Code', 'Tools', 'Training Techniques']
---
Current methods for Knowledge45;Based Question Answering (KBQA) usually rely on complex training techniques and model frameworks leading to many limitations in practical applications. Recently the emergence of In45;Context Learning (ICL) capabilities in Large Language Models (LLMs) provides a simple and training45;free semantic parsing paradigm for KBQA Given a small number of questions and their labeled logical forms as demo examples LLMs can understand the task intent and generate the logic form for a new question. However current powerful LLMs have little exposure to logic forms during pre45;training resulting in a high format error rate. To solve this problem we propose a code45;style in45;context learning method for KBQA which converts the generation process of unfamiliar logical form into the more familiar code generation process for LLMs. Experimental results on three mainstream datasets show that our method dramatically mitigated the formatting error problem in generating logic forms while realizing a new SOTA on WebQSP GrailQA and GraphQ under the few45;shot setting. The code and supplementary files are released at https://github.com/Arthurizijar/KB&#45;Coder .
