---
layout: publication
title: 'Towards Interpreting Language Models: A Case Study In Multi-hop Reasoning'
authors: Mansi Sakarvadia
conference: "Arxiv"
year: 2024
bibkey: sakarvadia2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05037"}
tags: ['GPT', 'Ethics and Bias', 'Model Architecture', 'Attention Mechanism', 'Prompting']
---
Answering multi-hop reasoning questions requires retrieving and synthesizing
information from diverse sources. Language models (LMs) struggle to perform
such reasoning consistently. We propose an approach to pinpoint and rectify
multi-hop reasoning failures through targeted memory injections on LM attention
heads. First, we analyze the per-layer activations of GPT-2 models in response
to single- and multi-hop prompts. We then propose a mechanism that allows users
to inject relevant prompt-specific information, which we refer to as
"memories," at critical LM locations during inference. By thus enabling the LM
to incorporate additional relevant information during inference, we enhance the
quality of multi-hop prompt completions. We empirically show that a simple,
efficient, and targeted memory injection into a key attention layer often
increases the probability of the desired next token in multi-hop tasks, by up
to 424%. We observe that small subsets of attention heads can significantly
impact the model prediction during multi-hop reasoning. To more faithfully
interpret these heads, we develop Attention Lens: an open source tool that
translates the outputs of attention heads into vocabulary tokens via learned
transformations called lenses. We demonstrate the use of lenses to reveal how a
model arrives at its answer and use them to localize sources of model failures
such as in the case of biased and malicious language generation.
