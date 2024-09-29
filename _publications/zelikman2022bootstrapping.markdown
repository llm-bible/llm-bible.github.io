---
layout: publication
title: Star Bootstrapping Reasoning With Reasoning
authors: Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman
conference: "Arxiv"
year: 2022
bibkey: zelikman2022bootstrapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2203.14465v2"}
tags: ['Applications', 'Prompting', 'RAG']
---
Generating step45;by45;step chain45;of45;thought rationales improves language model performance on complex reasoning tasks like mathematics or commonsense question45;answering. However inducing language model rationale generation currently requires either constructing massive rationale datasets or sacrificing accuracy by using only few45;shot inference. We propose a technique to iteratively leverage a small number of rationale examples and a large dataset without rationales to bootstrap the ability to perform successively more complex reasoning. This technique the Self45;Taught Reasoner (STaR) relies on a simple loop generate rationales to answer many questions prompted with a few rationale examples; if the generated answers are wrong try again to generate a rationale given the correct answer; fine45;tune on all the rationales that ultimately yielded correct answers; repeat. We show that STaR significantly improves performance on multiple datasets compared to a model fine45;tuned to directly predict final answers and performs comparably to fine45;tuning a 30× larger state45;of45;the45;art language model on CommensenseQA. Thus STaR lets a model improve itself by learning from its own generated reasoning.
