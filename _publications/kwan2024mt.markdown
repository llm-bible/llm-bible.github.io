---
layout: publication
title: 'Mt-eval: A Multi-turn Capabilities Evaluation Benchmark For Large Language Models'
authors: Wai-chung Kwan, Xingshan Zeng, Yuxin Jiang, Yufei Wang, Liangyou Li, Lifeng Shang, Xin Jiang, Qun Liu, Kam-fai Wong
conference: "Arxiv"
year: 2024
bibkey: kwan2024mt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16745"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Applications']
---
Large language models (LLMs) are increasingly relied upon for complex
multi-turn conversations across diverse real-world applications. However,
existing benchmarks predominantly focus on single-turn evaluations, overlooking
the models' capabilities in multi-turn interactions. To address this gap, we
introduce MT-Eval, a comprehensive benchmark designed to evaluate multi-turn
conversational abilities. By analyzing human-LLM conversations, we categorize
interaction patterns into four types: recollection, expansion, refinement, and
follow-up. We construct multi-turn queries for each category either by
augmenting existing datasets or by creating new examples with GPT-4 to avoid
data leakage. To study the factors impacting multi-turn abilities, we create
single-turn versions of the 1170 multi-turn queries and compare performance.
Our evaluation of 11 well-known LLMs shows that while closed-source models
generally surpass open-source ones, certain open-source models exceed
GPT-3.5-Turbo in specific tasks. We observe significant performance degradation
in multi-turn settings compared to single-turn settings in most models, which
is not correlated with the models' fundamental capabilities. Moreover, we
identify the distance to relevant content and susceptibility to error
propagation as the key factors influencing multi-turn performance. MT-Eval is
released publicly to encourage future research towards more robust
conversational models.
