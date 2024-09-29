---
layout: publication
title: Syntactic Structure Distillation Pretraining For Bidirectional Encoders
authors: Kuncoro Adhiguna, Kong Lingpeng, Fried Daniel, Yogatama Dani, Rimell Laura, Dyer Chris, Blunsom Phil
conference: "Arxiv"
year: 2020
bibkey: kuncoro2020syntactic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.13482"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Textual representation learners trained on large amounts of data have achieved notable success on downstream tasks; intriguingly they have also performed well on challenging tests of syntactic competence. Given this success it remains an open question whether scalable learners like BERT can become fully proficient in the syntax of natural language by virtue of data scale alone or whether they still benefit from more explicit syntactic biases. To answer this question we introduce a knowledge distillation strategy for injecting syntactic biases into BERT pretraining by distilling the syntactically informative predictions of a hierarchical---albeit harder to scale---syntactic language model. Since BERT models masked words in bidirectional context we propose to distill the approximate marginal distribution over words in context from the syntactic LM. Our approach reduces relative error by 2-21 on a diverse set of structured prediction tasks although we obtain mixed results on the GLUE benchmark. Our findings demonstrate the benefits of syntactic biases even in representation learners that exploit large amounts of data and contribute to a better understanding of where syntactic biases are most helpful in benchmarks of natural language understanding.
