---
layout: publication
title: 'Embedding Self-correction As An Inherent Ability In Large Language Models For Enhanced Mathematical Reasoning'
authors: Kuofeng Gao, Huanqia Cai, Qingyao Shuai, Dihong Gong, Zhifeng Li
conference: "Arxiv"
year: 2024
bibkey: gao2024embedding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10735'}
tags: ['Training Techniques', 'GPT', 'Tools', 'Fine-Tuning', 'Model Architecture', 'Pretraining Methods']
---
Accurate mathematical reasoning with Large Language Models (LLMs) is crucial
in revolutionizing domains that heavily rely on such reasoning. However, LLMs
often encounter difficulties in certain aspects of mathematical reasoning,
leading to flawed reasoning and erroneous results. To mitigate these issues, we
introduce a novel mechanism, the Chain of Self-Correction (CoSC), specifically
designed to embed self-correction as an inherent ability in LLMs, enabling them
to validate and rectify their own results. The CoSC mechanism operates through
a sequence of self-correction stages. In each stage, the LLMs generate a
program to address a given problem, execute this program using program-based
tools to obtain an output, subsequently verify this output. Based on the
verification, the LLMs either proceed to the next correction stage or finalize
the answer. This iterative self-correction process allows the LLMs to refine
its reasoning steps and improve the accuracy of its mathematical reasoning. We
implement CoSC using a two-phase fine-tuning approach. First, LLMs are trained
with a relatively small volume of seeding data generated from GPT-4. Then, we
enhance CoSC by training with a larger volume of self-generated data, without
relying on GPT-4. Experiments show that CoSC significantly boosts performance
on standard mathematical datasets compared to existing open-source LLMs.
Notably, our CoSC-Code-34B model achieved a 53.5% score on the challenging MATH
dataset, outperforming models like ChatGPT, GPT-4, and multi-modal LLMs such as
GPT-4V and Gemini-1.0. Importantly, CoSC operates in a zero-shot manner without
requiring demonstrations.
