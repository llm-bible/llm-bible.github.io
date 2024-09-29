---
layout: publication
title: Can Llms Reason In The Wild With Programs
authors: Yang Yuan, Xiong Siheng, Payani Ali, Shareghi Ehsan, Fekri Faramarz
conference: "Arxiv"
year: 2024
bibkey: yang2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13764"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have shown superior capability to solve reasoning problems with programs. While being a promising direction most of such frameworks are trained and evaluated in settings with a prior knowledge of task requirements. However as LLMs become more capable it is necessary to assess their reasoning abilities in more realistic scenarios where many real45;world problems are open45;ended with ambiguous scope and often require multiple formalisms to solve. To investigate this we introduce the task of reasoning in the wild where an LLM is tasked to solve a reasoning problem of unknown type by identifying the subproblems and their corresponding formalisms and writing a program to solve each subproblem guided by a tactic. We create a large tactic45;guided trajectory dataset containing detailed solutions to a diverse set of reasoning problems ranging from well45;defined single45;form reasoning (e.g. math logic) to ambiguous and hybrid ones (e.g. commonsense combined math and logic). This allows us to test various aspects of LLMs reasoning at the fine45;grained level such as the selection and execution of tactics and the tendency to take undesired shortcuts. In experiments we highlight that existing LLMs fail significantly on problems with ambiguous and mixed scope revealing critical limitations and overfitting issues (e.g. accuracy on GSM8K drops by at least 5037;). We further show the potential of finetuning a local LLM on the tactic45;guided trajectories in achieving better performance. Project repo is available at github.com/gblackout/Reason45;in45;the45;Wild
