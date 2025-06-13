---
layout: publication
title: 'Uniicl: An Efficient Unified Framework Unifying Compression, Selection, And Generation'
authors: Jun Gao, Qi Lv, Zili Wang, Tianxiang Wu, Ziqiang Cao, Wenjie Li
conference: "Arxiv"
year: 2024
bibkey: gao2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.17062'}
tags: ['Prompting', 'Efficiency and Optimization', 'In-Context Learning', 'Tools']
---
In-context learning (ICL) enhances the reasoning abilities of Large Language Models (LLMs) by prepending a few demonstrations. It motivates researchers to introduce more examples to provide additional contextual information for the generation. However, existing methods show a significant limitation due to the problem of excessive growth in context length, which causes a large hardware burden. In addition, shallow-relevant examples selected by off-the-shelf tools hinder LLMs from capturing useful contextual information for generation. In this paper, we propose \textbf\{UniICL\}, a novel \textbf\{Uni\}fied \textbf\{ICL\} framework that unifies demonstration compression, demonstration selection, and final response generation. Furthermore, to boost inference efficiency, we design a tailored compression strategy that allows UniICL to cache compression results into \textbf\{Demonstration Bank\} (\textbf\{DB\}), which avoids repeated compression of the same demonstration. Extensive out-of-domain evaluations prove the advantages of UniICL in both effectiveness and efficiency.
