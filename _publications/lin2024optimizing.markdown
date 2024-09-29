---
layout: publication
title: Optimizing Language Models For Human Preferences Is A Causal Inference Problem
authors: Lin Victoria, Ben-michael Eli, Morency Louis-philippe
conference: "Arxiv"
year: 2024
bibkey: lin2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14979"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Security']
---
As large language models (LLMs) see greater use in academic and commercial settings there is increasing interest in methods that allow language models to generate texts aligned with human preferences. In this paper we present an initial exploration of language model optimization for human preferences from direct outcome datasets where each sample consists of a text and an associated numerical outcome measuring the readers response. We first propose that language model optimization should be viewed as a causal problem to ensure that the model correctly learns the relationship between the text and the outcome. We formalize this causal language optimization problem and we develop a method--causal preference optimization (CPO)--that solves an unbiased surrogate objective for the problem. We further extend CPO with doubly robust CPO (DR-CPO) which reduces the variance of the surrogate objective while retaining provably strong guarantees on bias. Finally we empirically demonstrate the effectiveness of (DR-)CPO in optimizing state-of-the-art LLMs for human preferences on direct outcome data and we validate the robustness of DR-CPO under difficult confounding conditions.
