---
layout: publication
title: Enhancing Recommendation Diversity By Re45;ranking With Large Language Models
authors: Diego Carraro, Derek Bridge
conference: "Arxiv"
year: 2024
bibkey: carraro2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2401.11506v2"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
It has long been recognized that it is not enough for a Recommender System (RS) to provide recommendations based only on their relevance to users. Among many other criteria the set of recommendations may need to be diverse. Diversity is one way of handling recommendation uncertainty and ensuring that recommendations offer users a meaningful choice. The literature reports many ways of measuring diversity and improving the diversity of a set of recommendations most notably by re45;ranking and selecting from a larger set of candidate recommendations. Driven by promising insights from the literature on how to incorporate versatile Large Language Models (LLMs) into the RS pipeline in this paper we show how LLMs can be used for diversity re45;ranking. We begin with an informal study that verifies that LLMs can be used for re45;ranking tasks and do have some understanding of the concept of item diversity. Then we design a more rigorous methodology where LLMs are prompted to generate a diverse ranking from a candidate ranking using various prompt templates with different re45;ranking instructions in a zero45;shot fashion. We conduct comprehensive experiments testing state45;of45;the45;art LLMs from the GPT and Llama families. We compare their re45;ranking capabilities with random re45;ranking and various traditional re45;ranking methods from the literature. We open45;source the code of our experiments for reproducibility. Our findings suggest that the trade45;offs (in terms of performance and costs among others) of LLM45;based re45;rankers are superior to those of random re45;rankers but as yet inferior to the ones of traditional re45;rankers. However the LLM approach is promising. LLMs exhibit improved performance on many natural language processing and recommendation tasks and lower inference costs. Given these trends we can expect LLM45;based re45;ranking to become more competitive soon.
