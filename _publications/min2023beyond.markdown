---
layout: publication
title: Beyond Accuracy Evaluating Self45;consistency Of Code Large Language Models With Identitychain
authors: Min Marcus J., Ding Yangruibo, Buratti Luca, Pujar Saurabh, Kaiser Gail, Jana Suman, Ray Baishakhi
conference: "Arxiv"
year: 2023
bibkey: min2023beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14053"}
  - {name: "Code", url: "https://github.com/marcusm117/IdentityChain"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Code Large Language Models (Code LLMs) are being increasingly employed in real45;life applications so evaluating them is critical. While the conventional accuracy evaluates the performance of Code LLMs on a set of individual tasks their self45;consistency across different tasks is overlooked. Intuitively a trustworthy model should be self45;consistent when generating natural language specifications for its own code and generating code for its own specifications. Failure to preserve self45;consistency reveals a lack of understanding of the shared semantics underlying natural language and programming language and therefore undermines the trustworthiness of a model. In this paper we first formally define the self45;consistency of Code LLMs and then design a framework IdentityChain which effectively and efficiently evaluates the self45;consistency and conventional accuracy of a model at the same time. We study eleven Code LLMs and show that they fail to preserve self45;consistency which is indeed a distinct aspect from conventional accuracy. Furthermore we show that IdentityChain can be used as a model debugging tool to expose weaknesses of Code LLMs by demonstrating three major weaknesses that we identify in current models using IdentityChain. Our code is available at https://github.com/marcusm117/IdentityChain.
