---
layout: publication
title: A Simple Baseline For Knowledge45;based Visual Question Answering
authors: Xenos Alexandros, Stafylakis Themos, Patras Ioannis, Tzimiropoulos Georgios
conference: "Arxiv"
year: 2023
bibkey: xenos2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13570"}
  - {name: "Code", url: "https://github.com/alexandrosXe/ASimple&#45;Baseline&#45;For&#45;Knowledge&#45;Based&#45;VQA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques']
---
This paper is on the problem of Knowledge45;Based Visual Question Answering (KB45;VQA). Recent works have emphasized the significance of incorporating both explicit (through external databases) and implicit (through LLMs) knowledge to answer questions requiring external knowledge effectively. A common limitation of such approaches is that they consist of relatively complicated pipelines and often heavily rely on accessing GPT45;3 API. Our main contribution in this paper is to propose a much simpler and readily reproducible pipeline which in a nutshell is based on efficient in45;context learning by prompting LLaMA (1 and 2) using question45;informative captions as contextual information. Contrary to recent approaches our method is training45;free does not require access to external databases or APIs and yet achieves state45;of45;the45;art accuracy on the OK45;VQA and A45;OK45;VQA datasets. Finally we perform several ablation studies to understand important aspects of our method. Our code is publicly available at https://github.com/alexandrosXe/ASimple&#45;Baseline&#45;For&#45;Knowledge&#45;Based&#45;VQA
