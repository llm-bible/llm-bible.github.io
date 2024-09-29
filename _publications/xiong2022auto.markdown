---
layout: publication
title: Autoqgs Auto45;prompt For Low45;resource Knowledge45;based Question Generation From SPARQL
authors: Xiong Guanming, Bao Junwei, Zhao Wen, Wu Youzheng, He Xiaodong
conference: "Arxiv"
year: 2022
bibkey: xiong2022auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.12461"}
tags: ['Applications', 'Prompting']
---
This study investigates the task of knowledge45;based question generation (KBQG). Conventional KBQG works generated questions from fact triples in the knowledge graph which could not express complex operations like aggregation and comparison in SPARQL. Moreover due to the costly annotation of large45;scale SPARQL45;question pairs KBQG from SPARQL under low45;resource scenarios urgently needs to be explored. Recently since the generative pre45;trained language models (PLMs) typically trained in natural language (NL)45;to45;NL paradigm have been proven effective for low45;resource generation e.g. T5 and BART how to effectively utilize them to generate NL45;question from non45;NL SPARQL is challenging. To address these challenges AutoQGS an auto45;prompt approach for low45;resource KBQG from SPARQL is proposed. Firstly we put forward to generate questions directly from SPARQL for the KBQG task to handle complex operations. Secondly we propose an auto45;prompter trained on large45;scale unsupervised data to rephrase SPARQL into NL description smoothing the low45;resource transformation from non45;NL SPARQL to NL question with PLMs. Experimental results on the WebQuestionsSP ComlexWebQuestions 1.1 and PathQuestions show that our model achieves state45;of45;the45;art performance especially in low45;resource settings. Furthermore a corpus of 330k factoid complex question45;SPARQL pairs is generated for further KBQG research.
