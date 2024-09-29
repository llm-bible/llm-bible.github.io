---
layout: publication
title: Improving Compositional Generalization With Self45;training For Data45;to45;text Generation
authors: Mehta Sanket Vaibhav, Rao Jinfeng, Tay Yi, Kale Mihir, Parikh Ankur P., Strubell Emma
conference: "Arxiv"
year: 2021
bibkey: mehta2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08467"}
tags: ['Applications', 'Language Modeling', 'Training Techniques']
---
Data45;to45;text generation focuses on generating fluent natural language responses from structured meaning representations (MRs). Such representations are compositional and it is costly to collect responses for all possible combinations of atomic meaning schemata thereby necessitating few45;shot generalization to novel MRs. In this work we systematically study the compositional generalization of the state45;of45;the45;art T5 models in few45;shot data45;to45;text tasks. We show that T5 models fail to generalize to unseen MRs and we propose a template45;based input representation that considerably improves the models generalization capability. To further improve the models performance we propose an approach based on self45;training using fine45;tuned BLEURT for pseudo response selection. On the commonly45;used SGD and Weather benchmarks the proposed self45;training approach improves tree accuracy by 4637;+ and reduces the slot error rates by 7337;+ over the strong T5 baselines in few45;shot settings.
