---
layout: publication
title: User Simulation With Large Language Models For Evaluating Task45;oriented Dialogue
authors: Davidson Sam, Romeo Salvatore, Shu Raphael, Gung James, Gupta Arshit, Mansour Saab, Zhang Yi
conference: "Arxiv"
year: 2023
bibkey: davidson2023user
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13233"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
One of the major impediments to the development of new task45;oriented dialogue (TOD) systems is the need for human evaluation at multiple stages and iterations of the development process. In an effort to move toward automated evaluation of TOD we propose a novel user simulator built using recently developed large pretrained language models (LLMs). In order to increase the linguistic diversity of our system relative to the related previous work we do not fine45;tune the LLMs used by our system on existing TOD datasets; rather we use in45;context learning to prompt the LLMs to generate robust and linguistically diverse output with the goal of simulating the behavior of human interlocutors. Unlike previous work which sought to maximize goal success rate (GSR) as the primary metric of simulator performance our goal is a system which achieves a GSR similar to that observed in human interactions with TOD systems. Using this approach our current simulator is effectively able to interact with several TOD systems especially on single45;intent conversational goals while generating lexically and syntactically diverse output relative to previous simulators that rely upon fine45;tuned models. Finally we collect a Human2Bot dataset of humans interacting with the same TOD systems with which we experimented in order to better quantify these achievements.
