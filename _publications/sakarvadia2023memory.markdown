---
layout: publication
title: 'Memory Injections: Correcting Multi-hop Reasoning Failures During Inference In Transformer-based Language Models'
authors: Mansi Sakarvadia, Aswathy Ajith, Arham Khan, Daniel Grzenda, Nathaniel Hudson, André Bauer, Kyle Chard, Ian Foster
conference: "Arxiv"
year: 2023
bibkey: sakarvadia2023memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.05605'}
tags: ['Attention Mechanism', 'Transformer', 'GPT', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
Answering multi-hop reasoning questions requires retrieving and synthesizing
information from diverse sources. Large Language Models (LLMs) struggle to
perform such reasoning consistently. Here we propose an approach to pinpoint
and rectify multi-hop reasoning failures through targeted memory injections on
LLM attention heads. First, we analyze the per-layer activations of GPT-2
models in response to single and multi-hop prompts. We then propose a mechanism
that allows users to inject pertinent prompt-specific information, which we
refer to as "memories," at critical LLM locations during inference. By thus
enabling the LLM to incorporate additional relevant information during
inference, we enhance the quality of multi-hop prompt completions. We show
empirically that a simple, efficient, and targeted memory injection into a key
attention layer can often increase the probability of the desired next token in
multi-hop tasks, by up to 424%.
