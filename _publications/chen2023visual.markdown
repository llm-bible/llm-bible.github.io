---
layout: publication
title: Visual Instruction Tuning With Polite Flamingo
authors: Chen Delong, Liu Jianfeng, Dai Wenliang, Wang Baoyuan
conference: "Arxiv"
year: 2023
bibkey: chen2023visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.01003"}
tags: ['Pretraining Methods', 'Reinforcement Learning']
---
Recent research has demonstrated that the multi45;task fine45;tuning of multi45;modal Large Language Models (LLMs) using an assortment of annotated downstream vision45;language datasets significantly enhances their performance. Yet during this process a side effect which we termed as the multi45;modal alignment tax surfaces. This side effect negatively impacts the models ability to format responses appropriately 45;45; for instance its politeness 45;45; due to the overly succinct and unformatted nature of raw annotations resulting in reduced human preference. In this paper we introduce Polite Flamingo a multi45;modal response rewriter that transforms raw annotations into a more appealing polite format. Polite Flamingo is trained to reconstruct high45;quality responses from their automatically distorted counterparts and is subsequently applied to a vast array of vision45;language datasets for response rewriting. After rigorous filtering we generate the PF45;1M dataset and further validate its value by fine45;tuning a multi45;modal LLM with it. Combined with novel methodologies including U45;shaped multi45;stage tuning and multi45;turn augmentation the resulting model Clever Flamingo demonstrates its advantages in both multi45;modal understanding and response politeness according to automated and human evaluations.
