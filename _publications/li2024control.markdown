---
layout: publication
title: 'Control Large Language Models Via Divide And Conquer'
authors: Bingxuan Li, Yiwei Wang, Tao Meng, Kai-wei Chang, Nanyun Peng
conference: "Arxiv"
year: 2024
bibkey: li2024control
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04628'}
tags: ['Ethics and Bias', 'Language Modeling', 'Prompting', 'Applications']
---
This paper investigates controllable generation for large language models
(LLMs) with prompt-based control, focusing on Lexically Constrained Generation
(LCG). We systematically evaluate the performance of LLMs on satisfying lexical
constraints with prompt-based control, as well as their efficacy in downstream
applications. We conclude that LLMs face significant challenges in consistently
satisfying lexical constraints with prompt-based control. We identified three
key limitations of LLMs for LCG, including (1) position bias, where LLMs tend
to satisfy constraints that appear in specific positions within the input; (2)
low responsiveness to decoding parameters, which render minimal impact on
control of LLMs; and (3) struggle with handling the inherent complexity of
certain constraints (e.g., compound words). To address these issues, we
introduce a Divide and Conquer Generation strategy, effective for both
white-box and black-box LLMs, to enhance LLMs performance in LCG tasks, which
demonstrates over 90% improvement on success rate in the most challenging LCG
task. Our analysis provides valuable insights into the performance of LLMs in
LCG with prompt-based control, and our proposed strategy offers a pathway to
more sophisticated and customized text generation applications.
