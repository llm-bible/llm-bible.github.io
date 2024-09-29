---
layout: publication
title: Chainpoll A high efficacy method for LLM hallucination detection
authors: Friel Robert, Sanyal Atindriyo
conference: "Arxiv"
year: 2023
bibkey: friel2023chainpoll
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18344"}
tags: ['Ethics And Bias', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) have experienced notable advancements in generating coherent and contextually relevant responses. However hallucinations - incorrect or unfounded claims - are still prevalent prompting the creation of automated metrics to detect these in LLM outputs. Our contributions include introducing ChainPoll an innovative hallucination detection method that excels compared to its counterparts and unveiling RealHall a refined collection of benchmark datasets to assess hallucination detection metrics from recent studies. While creating RealHall we assessed tasks and datasets from previous hallucination detection studies and observed that many are not suitable for the potent LLMs currently in use. Overcoming this we opted for four datasets challenging for modern LLMs and pertinent to real-world scenarios. Using RealHall we conducted a comprehensive comparison of ChainPoll with numerous hallucination metrics from recent studies. Our findings indicate that ChainPoll outperforms in all RealHall benchmarks achieving an overall AUROC of 0.781. This surpasses the next best theoretical method by 11 and exceeds industry standards by over 23. Additionally ChainPoll is cost-effective and offers greater transparency than other metrics. We introduce two novel metrics to assess LLM hallucinations Adherence and Correctness. Adherence is relevant to Retrieval Augmented Generation workflows evaluating an LLMs analytical capabilities within given documents and contexts. In contrast Correctness identifies logical and reasoning errors.
