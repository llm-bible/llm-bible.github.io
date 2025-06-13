---
layout: publication
title: 'Template-driven Llm-paraphrased Framework For Tabular Math Word Problem Generation'
authors: Xiaoqiang Kang, Zimu Wang, Xiaobo Jin, Wei Wang, Kaizhu Huang, Qiufeng Wang
conference: "Arxiv"
year: 2024
bibkey: kang2024template
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15594'}
  - {name: "Code", url: 'https://github.com/Jason8Kang/TELL'}
tags: ['Has Code', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Solving tabular math word problems (TMWPs) has become a critical role in
evaluating the mathematical reasoning ability of large language models (LLMs),
where large-scale TMWP samples are commonly required for LLM fine-tuning. Since
the collection of high-quality TMWP datasets is costly and time-consuming,
recent research has concentrated on automatic TMWP generation. However, current
generated samples usually suffer from issues of either correctness or
diversity. In this paper, we propose a Template-driven LLM-paraphrased (TeLL)
framework for generating high-quality TMWP samples with diverse backgrounds and
accurate tables, questions, answers, and solutions. To this end, we first
extract templates from existing real samples to generate initial problems,
ensuring correctness. Then, we adopt an LLM to extend templates and paraphrase
problems, obtaining diverse TMWP samples. Furthermore, we find the reasoning
annotation is important for solving TMWPs. Therefore, we propose to enrich each
solution with illustrative reasoning steps. Through the proposed framework, we
construct a high-quality dataset TabMWP-TeLL by adhering to the question types
in the TabMWP dataset, and we conduct extensive experiments on a variety of
LLMs to demonstrate the effectiveness of TabMWP-TeLL in improving TMWP solving
performance. The code and data of this paper are available at:
https://github.com/Jason8Kang/TELL.
