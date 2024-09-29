---
layout: publication
title: GPT45;4 Doesnt Know Its Wrong An Analysis Of Iterative Prompting For Reasoning Problems
authors: Stechly Kaya, Marquez Matthew, Kambhampati Subbarao
conference: "Arxiv"
year: 2023
bibkey: stechly2023gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12397"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
There has been considerable divergence of opinion on the reasoning abilities of Large Language Models (LLMs). While the initial optimism that reasoning might emerge automatically with scale has been tempered thanks to a slew of counterexamples a wide spread belief in their iterative self45;critique capabilities persists. In this paper we set out to systematically investigate the effectiveness of iterative prompting of LLMs in the context of Graph Coloring a canonical NP45;complete reasoning problem that is related to propositional satisfiability as well as practical problems like scheduling and allocation. We present a principled empirical study of the performance of GPT4 in solving graph coloring instances or verifying the correctness of candidate colorings. In iterative modes we experiment with the model critiquing its own answers and an external correct reasoner verifying proposed solutions. In both cases we analyze whether the content of the criticisms actually affects bottom line performance. The study seems to indicate that (i) LLMs are bad at solving graph coloring instances (ii) they are no better at verifying a solution45;45;and thus are not effective in iterative modes with LLMs critiquing LLM45;generated solutions (iii) the correctness and content of the criticisms45;45;whether by LLMs or external solvers45;45;seems largely irrelevant to the performance of iterative prompting. We show that the observed increase in effectiveness is largely due to the correct solution being fortuitously present in the top45;k completions of the prompt (and being recognized as such by an external verifier). Our results thus call into question claims about the self45;critiquing capabilities of state of the art LLMs.
