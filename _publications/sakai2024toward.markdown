---
layout: publication
title: Toward the Evaluation of Large Language Models Considering Score Variance across Instruction Templates
authors: Sakai Yusuke, Nohejl Adam, Hang Jiangnan, Kamigaito Hidetaka, Watanabe Taro
conference: "Arxiv"
year: 2024
bibkey: sakai2024toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12263"}
tags: ['Applications', 'Prompting']
---
The natural language understanding (NLU) performance of large language models (LLMs) has been evaluated across various tasks and datasets. The existing evaluation methods however do not take into account the variance in scores due to differences in prompts which leads to unfair evaluation and comparison of NLU performance. Moreover evaluation designed for specific prompts is inappropriate for instruction tuning which aims to perform well with any prompt. It is therefore necessary to find a way to measure NLU performance in a fair manner considering score variance between different instruction templates. In this study we provide English and Japanese cross-lingual datasets for evaluating the NLU performance of LLMs which include multiple instruction templates for fair evaluation of each task along with regular expressions to constrain the output format. Furthermore we propose the Sharpe score as an evaluation metric that takes into account the variance in scores between templates. Comprehensive analysis of English and Japanese LLMs reveals that the high variance among templates has a significant impact on the fair evaluation of LLMs.
