---
layout: publication
title: 'A Cause-effect Look At Alleviating Hallucination Of Knowledge-grounded Dialogue Generation'
authors: Jifan Yu, Xiaohan Zhang, Yifan Xu, Xuanyu Lei, Zijun Yao, Jing Zhang, Lei Hou, Juanzi Li
conference: "Arxiv"
year: 2024
bibkey: yu2024cause
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03491"}
tags: ['Model Architecture', 'Applications', 'Attention Mechanism', 'Reinforcement Learning']
---
Empowered by the large-scale pretrained language models, existing dialogue
systems have demonstrated impressive performance conducting fluent and
natural-sounding conversations. However, they are still plagued by the
hallucination problem, causing unpredictable factual errors in the generated
responses. Recently, knowledge-grounded dialogue generation models, that
intentionally invoke external knowledge resources to more informative
responses, are also proven to be effective in reducing hallucination. Following
the idea of getting high-quality knowledge, a few efforts have achieved pretty
good performance on this issue. As some inevitable knowledge noises may also
lead to hallucinations, it is emergent to investigate the reason and future
directions for building noise-tolerant methods in KGD tasks. In this paper, we
analyze the causal story behind this problem with counterfactual reasoning
methods. Based on the causal effect analysis, we propose a possible solution
for alleviating the hallucination in KGD by exploiting the dialogue-knowledge
interaction. Experimental results of our example implementation show that this
method can reduce hallucination without disrupting other dialogue performance,
while keeping adaptive to different generation models. We hope our efforts can
support and call for more attention to developing lightweight techniques
towards robust and trusty dialogue systems.
