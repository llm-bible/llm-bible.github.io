---
layout: publication
title: 'Attention Is Not Explanation'
authors: Sarthak Jain, Byron C. Wallace
conference: "Arxiv"
year: 2019
bibkey: jain2019attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1902.10186"}
  - {name: "Code", url: "https://github.com/successar/AttentionExplanation"}
tags: ['Model Architecture', 'Ethics and Bias', 'Interpretability', 'Transformer', 'Has Code', 'Interpretability and Explainability', 'Attention Mechanism']
---
Attention mechanisms have seen wide adoption in neural NLP models. In
addition to improving predictive performance, these are often touted as
affording transparency: models equipped with attention provide a distribution
over attended-to input units, and this is often presented (at least implicitly)
as communicating the relative importance of inputs. However, it is unclear what
relationship exists between attention weights and model outputs. In this work,
we perform extensive experiments across a variety of NLP tasks that aim to
assess the degree to which attention weights provide meaningful `explanations'
for predictions. We find that they largely do not. For example, learned
attention weights are frequently uncorrelated with gradient-based measures of
feature importance, and one can identify very different attention distributions
that nonetheless yield equivalent predictions. Our findings show that standard
attention modules do not provide meaningful explanations and should not be
treated as though they do. Code for all experiments is available at
https://github.com/successar/AttentionExplanation.
