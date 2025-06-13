---
layout: publication
title: 'ACORN: Aspect-wise Commonsense Reasoning Explanation Evaluation'
authors: Ana Brassard, Benjamin Heinzerling, Keito Kudo, Keisuke Sakaguchi, Kentaro Inui
conference: "Arxiv"
year: 2024
bibkey: brassard2024aspect
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.04818'}
  - {name: "Code", url: 'https://github.com/a-brassard/ACORN'}
tags: ['RAG', 'Has Code', 'Efficiency and Optimization', 'Interpretability and Explainability']
---
Evaluating the quality of free-text explanations is a multifaceted,
subjective, and labor-intensive task. Large language models (LLMs) present an
appealing alternative due to their potential for consistency, scalability, and
cost-efficiency. In this work, we present ACORN, a new dataset of 3,500
free-text explanations and aspect-wise quality ratings, and use it to evaluate
how LLMs rate explanations. We observed that larger models outputted labels
that maintained or increased the inter-annotator agreement, suggesting that
they are within the expected variance between human raters. However, their
correlation with majority-voted human ratings varied across different quality
aspects, indicating that they are not a complete replacement. In turn, using
LLMs as a supplement to a smaller group of human raters in some cases improved
the correlation with the original majority labels. However, the effect was
limited to cases where human raters were scarce, and an additional human rater
had a more pronounced effect in all cases. Overall, we recommend against using
LLMs as a complete replacement for human raters but encourage using them in
configurations that end with targeted human involvement. Data available here:
https://github.com/a-brassard/ACORN
