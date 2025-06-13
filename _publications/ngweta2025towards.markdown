---
layout: publication
title: 'Towards Llms Robustness To Changes In Prompt Format Styles'
authors: Lilian Ngweta, Kiran Kate, Jason Tsay, Yara Rizk
conference: "Arxiv"
year: 2025
bibkey: ngweta2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06969"}
tags: ['Security', 'Few-Shot', 'Prompting', 'Applications']
---
Large language models (LLMs) have gained popularity in recent years for their
utility in various applications. However, they are sensitive to non-semantic
changes in prompt formats, where small changes in the prompt format can lead to
significant performance fluctuations. In the literature, this problem is
commonly referred to as prompt brittleness. Previous research on prompt
engineering has focused mainly on developing techniques for identifying the
optimal prompt for specific tasks. Some studies have also explored the issue of
prompt brittleness and proposed methods to quantify performance variations;
however, no simple solution has been found to address this challenge. We
propose Mixture of Formats (MOF), a simple and efficient technique for
addressing prompt brittleness in LLMs by diversifying the styles used in the
prompt few-shot examples. MOF was inspired by computer vision techniques that
utilize diverse style datasets to prevent models from associating specific
styles with the target variable. Empirical results show that our proposed
technique reduces style-induced prompt brittleness in various LLMs while also
enhancing overall performance across prompt variations and different datasets.
