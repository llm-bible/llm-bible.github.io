---
layout: publication
title: Dempt Decoding45;enhanced Multi45;phase Prompt Tuning For Making Llms Be Better Context45;aware Translators
authors: Lyu Xinglin, Li Junhui, Zhao Yanqing, Zhang Min, Wei Daimeng, Tao Shimin, Yang Hao, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: lyu2024decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15200"}
tags: ['Applications', 'Prompting']
---
Generally the decoder45;only large language models (LLMs) are adapted to context45;aware neural machine translation (NMT) in a concatenating way where LLMs take the concatenation of the source sentence (i.e. intra45;sentence context) and the inter45;sentence context as the input and then to generate the target tokens sequentially. This adaptation strategy i.e. concatenation mode considers intra45;sentence and inter45;sentence contexts with the same priority despite an apparent difference between the two kinds of contexts. In this paper we propose an alternative adaptation approach named Decoding45;enhanced Multi45;phase Prompt Tuning (DeMPT) to make LLMs discriminately model and utilize the inter45; and intra45;sentence context and more effectively adapt LLMs to context45;aware NMT. First DeMPT divides the context45;aware NMT process into three separate phases. During each phase different continuous prompts are introduced to make LLMs discriminately model various information. Second DeMPT employs a heuristic way to further discriminately enhance the utilization of the source45;side inter45; and intra45;sentence information at the final decoding phase. Experiments show that our approach significantly outperforms the concatenation method and further improves the performance of LLMs in discourse modeling.
