---
layout: publication
title: Codegen An Open Large Language Model For Code With Multi45;turn Program Synthesis
authors: Erik Nijkamp, Bo Pang, Hiroaki Hayashi, Lifu Tu, Huan Wang, Yingbo Zhou, Silvio Savarese, Caiming Xiong
conference: "Arxiv"
year: 2022
bibkey: nijkamp2022open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2203.13474v5"}
  - {name: "Code", url: "https://github.com/salesforce/CodeGen"}
tags: ['Applications', 'Has Code', 'Prompting', 'Tools', 'Training Techniques']
---
Program synthesis strives to generate a computer program as a solution to a given problem specification expressed with input45;output examples or natural language descriptions. The prevalence of large language models advances the state45;of45;the45;art for program synthesis though limited training resources and data impede open access to such models. To democratize this we train and release a family of large language models up to 16.1B parameters called CODEGEN on natural language and programming language data and open source the training library JAXFORMER. We show the utility of the trained model by demonstrating that it is competitive with the previous state45;of45;the45;art on zero45;shot Python code generation on HumanEval. We further investigate the multi45;step paradigm for program synthesis where a single program is factorized into multiple prompts specifying subproblems. To this end we construct an open benchmark Multi45;Turn Programming Benchmark (MTPB) consisting of 115 diverse problem sets that are factorized into multi45;turn prompts. Our analysis on MTPB shows that the same intent provided to CODEGEN in multi45;turn fashion significantly improves program synthesis over that provided as a single turn. We make the training library JAXFORMER and model checkpoints available as open source contribution https://github.com/salesforce/CodeGen.
