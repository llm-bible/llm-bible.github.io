---
layout: publication
title: 'Evaluating Interventional Reasoning Capabilities Of Large Language Models'
authors: Kasetty Tejas, Mahajan Divyat, Dziugaite Gintare Karolina, Drouin Alexandre, Sridhar Dhanya
conference: "Arxiv"
year: 2024
bibkey: kasetty2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05545"}
tags: ['GPT', 'Model Architecture', 'Prompting']
---
Numerous decision-making tasks require estimating causal effects under interventions on different parts of a system. As practitioners consider using large language models (LLMs) to automate decisions studying their causal reasoning capabilities becomes crucial. A recent line of work evaluates LLMs ability to retrieve commonsense causal facts but these evaluations do not sufficiently assess how LLMs reason about interventions. Motivated by the role that interventions play in causal inference in this paper we conduct empirical analyses to evaluate whether LLMs can accurately update their knowledge of a data-generating process in response to an intervention. We create benchmarks that span diverse causal graphs (e.g. confounding mediation) and variable types and enable a study of intervention-based reasoning. These benchmarks allow us to isolate the ability of LLMs to accurately predict changes resulting from their ability to memorize facts or find other shortcuts. Our analysis on four LLMs highlights that while GPT- 4 models show promising accuracy at predicting the intervention effects they remain sensitive to distracting factors in the prompts.
