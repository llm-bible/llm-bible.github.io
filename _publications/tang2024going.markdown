---
layout: publication
title: 'Going Beyond Word Matching: Syntax Improves In-context Example Selection For Machine Translation'
authors: Chenming Tang, Zhixiang Wang, Yunfang Wu
conference: "Arxiv"
year: 2024
bibkey: tang2024going
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19285"}
tags: ['Applications', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) is the trending prompting strategy in the era of
large language models (LLMs), where a few examples are demonstrated to evoke
LLMs' power for a given task. How to select informative examples remains an
open issue. Previous works on in-context example selection for machine
translation (MT) focus on superficial word-level features while ignoring deep
syntax-level knowledge. In this paper, we propose a syntax-based in-context
example selection method for MT, by computing the syntactic similarity between
dependency trees using Polynomial Distance. In addition, we propose an ensemble
strategy combining examples selected by both word-level and syntax-level
criteria. Experimental results between English and 6 common languages indicate
that syntax can effectively enhancing ICL for MT, obtaining the highest COMET
scores on 11 out of 12 translation directions.
