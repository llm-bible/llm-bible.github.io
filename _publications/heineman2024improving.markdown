---
layout: publication
title: Improving Minimum Bayes Risk Decoding With Multi45;prompt
authors: Heineman David, Dou Yao, Xu Wei
conference: "Arxiv"
year: 2024
bibkey: heineman2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15343"}
tags: ['Applications', 'Prompting']
---
While instruction fine45;tuned LLMs are effective text generators sensitivity to prompt construction makes performance unstable and sub45;optimal in practice. Relying on a single best prompt cannot capture all differing approaches to a generation problem. Using this observation we propose multi45;prompt decoding where many candidate generations are decoded from a prompt bank at inference45;time. To ensemble candidates we use Minimum Bayes Risk (MBR) decoding which selects a final output using a trained value metric. We show multi45;prompt improves MBR across a comprehensive set of conditional generation tasks and show this is a result of estimating a more diverse and higher quality candidate space than that of a single prompt. Further experiments confirm multi45;prompt improves generation across tasks models and metrics.
