---
layout: publication
title: 'Unveiling Code Pre-trained Models: Investigating Syntax And Semantics Capacities'
authors: Ma Wei, Liu Shangqing, Zhao Mengjie, Xie Xiaofei, Wang Wenhan, Hu Qiang, Zhang Jie, Liu Yang
conference: "Arxiv"
year: 2022
bibkey: ma2022unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10017"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
Past research has examined how well these models grasp code syntax, yet their understanding of code semantics still needs to be explored. We extensively analyze seven code models to investigate how code models represent code syntax and semantics. This includes four prominent code pre-trained models (CodeBERT, GraphCodeBERT, CodeT5, and UnixCoder) and three large language models (StarCoder, CodeLlama, and CodeT5+). We have developed four probing tasks to evaluate the models' abilities to learn code syntax and semantics. These tasks focus on reconstructing code syntax and semantic structures-such as AST, CFG, CDG, and DDG - within the models' representation spaces. These structures are fundamental to understanding code. Additionally, we explore the role of syntax tokens in each token representation and the extended dependencies among code tokens. Furthermore, we examine the distribution of attention weights concerning code semantic structures. Through detailed analysis, our results emphasize the strengths and weaknesses of various code models in mastering code syntax and semantics. The findings reveal that these models are proficient in grasping code syntax, effectively capturing the relationships and roles of syntax tokens. However, their ability to encode code semantics shows more variability. This study enriches our understanding of the capabilities of code models in analyzing syntax and semantics. Our findings offer valuable insights for future code model enhancements, helping optimize their application across a range of code-related tasks.
