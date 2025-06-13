---
layout: publication
title: 'Mutual Exclusivity Training And Primitive Augmentation To Induce Compositionality'
authors: Yichen Jiang, Xiang Zhou, Mohit Bansal
conference: "Arxiv"
year: 2022
bibkey: jiang2022mutual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.15578"}
  - {name: "Code", url: "https://github.com/owenzx/met-primaug"}
tags: ['Training Techniques', 'Model Architecture', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Recent datasets expose the lack of the systematic generalization ability in
standard sequence-to-sequence models. In this work, we analyze this behavior of
seq2seq models and identify two contributing factors: a lack of mutual
exclusivity bias (i.e., a source sequence already mapped to a target sequence
is less likely to be mapped to other target sequences), and the tendency to
memorize whole examples rather than separating structures from contents. We
propose two techniques to address these two issues respectively: Mutual
Exclusivity Training that prevents the model from producing seen generations
when facing novel, unseen examples via an unlikelihood-based loss; and
prim2primX data augmentation that automatically diversifies the arguments of
every syntactic function to prevent memorizing and provide a compositional
inductive bias without exposing test-set data. Combining these two techniques,
we show substantial empirical improvements using standard sequence-to-sequence
models (LSTMs and Transformers) on two widely-used compositionality datasets:
SCAN and COGS. Finally, we provide analysis characterizing the improvements as
well as the remaining challenges, and provide detailed ablations of our method.
Our code is available at https://github.com/owenzx/met-primaug
