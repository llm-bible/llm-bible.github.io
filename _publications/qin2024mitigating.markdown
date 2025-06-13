---
layout: publication
title: 'Mitigating Gender Bias In Code Large Language Models Via Model Editing'
authors: Zhanyue Qin, Haochuan Wang, Zecheng Wang, Deyuan Liu, Cunhang Fan, Zhao Lv, Zhiying Tu, Dianhui Chu, Dianbo Sui
conference: "Arxiv"
year: 2024
bibkey: qin2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07820"}
tags: ['Ethics and Bias', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
In recent years, with the maturation of large language model (LLM) technology
and the emergence of high-quality programming code datasets, researchers have
become increasingly confident in addressing the challenges of program synthesis
automatically. However, since most of the training samples for LLMs are
unscreened, it is inevitable that LLMs' performance may not align with
real-world scenarios, leading to the presence of social bias. To evaluate and
quantify the gender bias in code LLMs, we propose a dataset named CodeGenBias
(Gender Bias in the Code Generation) and an evaluation metric called FB-Score
(Factual Bias Score) based on the actual gender distribution of correlative
professions. With the help of CodeGenBias and FB-Score, we evaluate and analyze
the gender bias in eight mainstream Code LLMs. Previous work has demonstrated
that model editing methods that perform well in knowledge editing have the
potential to mitigate social bias in LLMs. Therefore, we develop a model
editing approach named MG-Editing (Multi-Granularity model Editing), which
includes the locating and editing phases. Our model editing method MG-Editing
can be applied at five different levels of model parameter granularity: full
parameters level, layer level, module level, row level, and neuron level.
Extensive experiments not only demonstrate that our MG-Editing can effectively
mitigate the gender bias in code LLMs while maintaining their general code
generation capabilities, but also showcase its excellent generalization. At the
same time, the experimental results show that, considering both the gender bias
of the model and its general code generation capability, MG-Editing is most
effective when applied at the row and neuron levels of granularity.
