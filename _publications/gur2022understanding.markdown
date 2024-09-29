---
layout: publication
title: Understanding HTML With Large Language Models
authors: Gur Izzeddin, Nachum Ofir, Miao Yingjie, Safdari Mustafa, Huang Austin, Chowdhery Aakanksha, Narang Sharan, Fiedel Noah, Faust Aleksandra
conference: "Arxiv"
year: 2022
bibkey: gur2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03945"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have shown exceptional performance on a variety of natural language tasks. Yet their capabilities for HTML understanding 45;45; i.e. parsing the raw HTML of a webpage with applications to automation of web45;based tasks crawling and browser45;assisted retrieval 45;45; have not been fully explored. We contribute HTML understanding models (fine45;tuned LLMs) and an in45;depth analysis of their capabilities under three tasks (i) Semantic Classification of HTML elements (ii) Description Generation for HTML inputs and (iii) Autonomous Web Navigation of HTML pages. While previous work has developed dedicated architectures and training procedures for HTML understanding we show that LLMs pretrained on standard natural language corpora transfer remarkably well to HTML understanding tasks. For instance fine45;tuned LLMs are 1237; more accurate at semantic classification compared to models trained exclusively on the task dataset. Moreover when fine45;tuned on data from the MiniWoB benchmark LLMs successfully complete 5037; more tasks using 192x less data compared to the previous best supervised model. Out of the LLMs we evaluate we show evidence that T545;based models are ideal due to their bidirectional encoder45;decoder architecture. To promote further research on LLMs for HTML understanding we create and open45;source a large45;scale HTML dataset distilled and auto45;labeled from CommonCrawl.
