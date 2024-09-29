---
layout: publication
title: Autoqgs\: Auto-prompt For Low-resource Knowledge-based Question Generation From SPARQL
authors: Xiong Guanming, Bao Junwei, Zhao Wen, Wu Youzheng, He Xiaodong
conference: "Arxiv"
year: 2022
bibkey: xiong2022auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.12461"}
tags: ['Applications', 'Prompting']
---
This study investigates the task of knowledge-based question generation (KBQG). Conventional KBQG works generated questions from fact triples in the knowledge graph which could not express complex operations like aggregation and comparison in SPARQL. Moreover due to the costly annotation of large-scale SPARQL-question pairs KBQG from SPARQL under low-resource scenarios urgently needs to be explored. Recently since the generative pre-trained language models (PLMs) typically trained in natural language (NL)-to-NL paradigm have been proven effective for low-resource generation e.g. T5 and BART how to effectively utilize them to generate NL-question from non-NL SPARQL is challenging. To address these challenges AutoQGS an auto-prompt approach for low-resource KBQG from SPARQL is proposed. Firstly we put forward to generate questions directly from SPARQL for the KBQG task to handle complex operations. Secondly we propose an auto-prompter trained on large-scale unsupervised data to rephrase SPARQL into NL description smoothing the low-resource transformation from non-NL SPARQL to NL question with PLMs. Experimental results on the WebQuestionsSP ComlexWebQuestions 1.1 and PathQuestions show that our model achieves state-of-the-art performance especially in low-resource settings. Furthermore a corpus of 330k factoid complex question-SPARQL pairs is generated for further KBQG research.
