---
layout: publication
title: 'Structtest: Benchmarking Llms'' Reasoning Through Compositional Structured Outputs'
authors: Hailin Chen, Fangkai Jiao, Mathieu Ravaut, Nawshad Farruque, Xuan Phi Nguyen, Chengwei Qin, Manan Dey, Bosheng Ding, Caiming Xiong, Shafiq Joty, Yingbo Zhou
conference: "Arxiv"
year: 2024
bibkey: chen2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18011"}
tags: ['Model Architecture', 'Tools', 'GPT', 'Ethics and Bias', 'Applications']
---
The rapid advancement of large language models (LLMs) demands robust,
unbiased, and scalable evaluation methods. However, human annotations are
costly to scale, model-based evaluations are susceptible to stylistic biases,
and target-answer-based benchmarks are vulnerable to data contamination and
cheating. To address these limitations, we propose StructTest, a novel
benchmark that evaluates LLMs on their ability to follow compositional
instructions and generate structured outputs, providing an unbiased,
cost-effective, and difficult-to-cheat evaluation framework. Assessments are
conducted deterministically using a rule-based evaluator, which can be easily
extended to new tasks and datasets. By testing structured outputs across
diverse domains including Summarization, Code, HTML, and Math, and evaluating
17 popular LLMs, we demonstrate that StructTest remains challenging even for
top-performing models like Deepseek-V3/R1 and GPT-4o, establishing it as a
robust proxy for measuring reasoning capabilities. We believe StructTest offers
a critical and complementary approach to achieving objective and comprehensive
model evaluation.
