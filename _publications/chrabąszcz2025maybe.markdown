---
layout: publication
title: 'Maybe I Should Not Answer That, But... Do Llms Understand The Safety Of Their Inputs?'
authors: Maciej Chrabąszcz, Filip Szatkowski, Bartosz Wójcik, Jan Dubiński, Tomasz Trzciński
conference: "Arxiv"
year: 2025
bibkey: chrabąszcz2025maybe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16174"}
tags: ['Responsible AI', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Prompting']
---
Ensuring the safety of the Large Language Model (LLM) is critical, but
currently used methods in most cases sacrifice the model performance to obtain
increased safety or perform poorly on data outside of their adaptation
distribution. We investigate existing methods for such generalization and find
them insufficient. Surprisingly, while even plain LLMs recognize unsafe
prompts, they may still generate unsafe responses. To avoid performance
degradation and preserve safe performance, we advocate for a two-step
framework, where we first identify unsafe prompts via a lightweight classifier,
and apply a "safe" model only to such prompts. In particular, we explore the
design of the safety detector in more detail, investigating the use of
different classifier architectures and prompting techniques. Interestingly, we
find that the final hidden state for the last token is enough to provide robust
performance, minimizing false positives on benign data while performing well on
malicious prompt detection. Additionally, we show that classifiers trained on
the representations from different model layers perform comparably on the
latest model layers, indicating that safety representation is present in the
LLMs' hidden states at most model stages. Our work is a step towards efficient,
representation-based safety mechanisms for LLMs.
