---
layout: publication
title: 'Stylized Dialogue Response Generation Using Stylized Unpaired Texts'
authors: Yinhe Zheng, Zikai Chen, Rongsheng Zhang, Shilei Huang, Xiaoxi Mao, Minlie Huang
conference: "Arxiv"
year: 2020
bibkey: zheng2020stylized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.12719"}
tags: ['Training Techniques', 'Applications']
---
Generating stylized responses is essential to build intelligent and engaging
dialogue systems. However, this task is far from well-explored due to the
difficulties of rendering a particular style in coherent responses, especially
when the target style is embedded only in unpaired texts that cannot be
directly used to train the dialogue model. This paper proposes a stylized
dialogue generation method that can capture stylistic features embedded in
unpaired texts. Specifically, our method can produce dialogue responses that
are both coherent to the given context and conform to the target style. In this
study, an inverse dialogue model is first introduced to predict possible posts
for the input responses, and then this inverse model is used to generate
stylized pseudo dialogue pairs based on these stylized unpaired texts. Further,
these pseudo pairs are employed to train the stylized dialogue model with a
joint training process, and a style routing approach is proposed to intensify
stylistic features in the decoder. Automatic and manual evaluations on two
datasets demonstrate that our method outperforms competitive baselines in
producing coherent and style-intensive dialogue responses.
