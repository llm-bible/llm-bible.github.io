---
layout: publication
title: BOOST Harnessing Black45;box Control To Boost Commonsense In Lms Generation
authors: Tian Yufei, Zhang Felix, Peng Nanyun
conference: "Arxiv"
year: 2023
bibkey: tian2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17054"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) such as GPT45;3 have demonstrated a strong capability to generate coherent and contextually relevant text. However amidst their successes a crucial issue persists their generated outputs still lack commonsense at times. Moreover fine45;tuning the entire LLM towards more commonsensical outputs is computationally expensive if not infeasible. In this paper we present a computation45;efficient framework that steers a frozen Pre45;Trained Language Model (PTLM) towards more commonsensical generation (i.e. producing a plausible output that incorporates a list of concepts in a meaningful way). Specifically we first construct a reference45;free evaluator that assigns a sentence with a commonsensical score by grounding the sentence to a dynamic commonsense knowledge base from four different relational aspects. We then use the scorer as the oracle for commonsense knowledge and extend the controllable generation method called NADO to train an auxiliary head that guides a fixed PTLM to better satisfy the oracle. We test our framework on a series of GPT45;245; Flan45;T545; and Alpaca45;based language models (LMs) on two constrained concept45;to45;sentence benchmarks. Human evaluation results demonstrate that our method consistently leads to the most commonsensical outputs.
