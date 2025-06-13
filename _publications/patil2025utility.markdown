---
layout: publication
title: 'UPCORE: Utility-preserving Coreset Selection For Balanced Unlearning'
authors: Vaidehi Patil, Elias Stengel-eskin, Mohit Bansal
conference: "Arxiv"
year: 2025
bibkey: patil2025utility
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15082"}
tags: ['Tools']
---
User specifications or legal frameworks often require information to be
removed from pretrained models, including large language models (LLMs). This
requires deleting or "forgetting" a set of data points from an already-trained
model, which typically degrades its performance on other data points. Thus, a
balance must be struck between removing information and keeping the model's
other abilities intact, with a failure to balance this trade-off leading to
poor deletion or an unusable model. To this end, we propose UPCORE
(Utility-Preserving Coreset Selection), a method-agnostic data selection
framework for mitigating collateral damage during unlearning. Finding that the
model damage is correlated with the variance of the model's representations on
the forget set, we selectively prune the forget set to remove outliers, thereby
minimizing model degradation after unlearning. We evaluate UPCORE across three
standard unlearning methods consistently achieving a superior balance between
the competing objectives of deletion efficacy and model preservation. To better
evaluate this trade-off, we introduce a new metric, measuring the
area-under-the-curve (AUC) across standard metrics. We find that UPCORE
improves both standard metrics and AUC, benefitting from positive transfer
between the coreset and pruned points while reducing negative transfer from the
forget set to points outside of it.
