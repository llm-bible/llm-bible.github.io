---
layout: publication
title: Mind The Instructions A Holistic Evaluation Of Consistency And Interactions In Prompt-based Learning
authors: Weber Lucas, Bruni Elia, Hupkes Dieuwke
conference: "Arxiv"
year: 2023
bibkey: weber2023mind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13486"}
tags: ['Prompting']
---
Finding the best way of adapting pre-trained language models to a task is a big challenge in current NLP. Just like the previous generation of task-tuned models (TT) models that are adapted to tasks via in-context-learning (ICL) are robust in some setups but not in others. Here we present a detailed analysis of which design choices cause instabilities and inconsistencies in LLM predictions. First we show how spurious correlations between input distributions and labels -- a known issue in TT models -- form only a minor problem for prompted models. Then we engage in a systematic holistic evaluation of different factors that have been found to influence predictions in a prompting setup. We test all possible combinations of a range of factors on both vanilla and instruction-tuned (IT) LLMs of different scale and statistically analyse the results to show which factors are the most influential interactive or stable. Our results show which factors can be used without precautions and which should be avoided or handled with care in most settings.
