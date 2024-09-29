---
layout: publication
title: 'Composing Answer From Multi-spans For Reading Comprehension'
authors: Zhang Zhuosheng, Zhang Yiqing, Zhao Hai, Zhou Xi, Zhou Xiang
conference: "Arxiv"
year: 2020
bibkey: zhang2020composing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.06141"}
tags: ['Applications']
---
This paper presents a novel method to generate answers for non-extraction machine reading comprehension (MRC) tasks whose answers cannot be simply extracted as one span from the given passages. Using a pointer network-style extractive decoder for such type of MRC may result in unsatisfactory performance when the ground-truth answers are given by human annotators or highly re-paraphrased from parts of the passages. On the other hand using generative decoder cannot well guarantee the resulted answers with well-formed syntax and semantics when encountering long sentences. Therefore to alleviate the obvious drawbacks of both sides we propose an answer making-up method from extracted multi-spans that are learned by our model as highly confident n-gram candidates in the given passage. That is the returned answers are composed of discontinuous multi-spans but not just one consecutive span in the given passages anymore. The proposed method is simple but effective empirical experiments on MS MARCO show that the proposed method has a better performance on accurately generating long answers and substantially outperforms two competitive typical one-span and Seq2Seq baseline decoders.
