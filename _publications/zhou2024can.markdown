---
layout: publication
title: 'Can Language Models Perform Robust Reasoning In Chain-of-thought Prompting With Noisy Rationales?'
authors: Zhanke Zhou, Rong Tao, Jianing Zhu, Yiwen Luo, Zengmao Wang, Bo Han
conference: "Arxiv"
year: 2024
bibkey: zhou2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23856'}
  - {name: "Code", url: 'https://github.com/tmlr-group/NoisyRationales'}
tags: ['Has Code', 'RAG', 'Security', 'Fine-Tuning', 'Prompting']
---
This paper investigates an under-explored challenge in large language models
(LLMs): chain-of-thought prompting with noisy rationales, which include
irrelevant or inaccurate reasoning thoughts within examples used for in-context
learning. We construct NoRa dataset that is tailored to evaluate the robustness
of reasoning in the presence of noisy rationales. Our findings on NoRa dataset
reveal a prevalent vulnerability to such noise among current LLMs, with
existing robust methods like self-correction and self-consistency showing
limited efficacy. Notably, compared to prompting with clean rationales, base
LLM drops by 1.4%-19.8% in accuracy with irrelevant thoughts and more
drastically by 2.2%-40.4% with inaccurate thoughts.
  Addressing this challenge necessitates external supervision that should be
accessible in practice. Here, we propose the method of contrastive denoising
with noisy chain-of-thought (CD-CoT). It enhances LLMs' denoising-reasoning
capabilities by contrasting noisy rationales with only one clean rationale,
which can be the minimal requirement for denoising-purpose prompting. This
method follows a principle of exploration and exploitation: (1) rephrasing and
selecting rationales in the input space to achieve explicit denoising and (2)
exploring diverse reasoning paths and voting on answers in the output space.
Empirically, CD-CoT demonstrates an average improvement of 17.8% in accuracy
over the base model and shows significantly stronger denoising capabilities
than baseline methods. The source code is publicly available at:
https://github.com/tmlr-group/NoisyRationales.
