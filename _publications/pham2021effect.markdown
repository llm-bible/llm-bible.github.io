---
layout: publication
title: 'The Effect Of Model Size On Worst-group Generalization'
authors: Pham Alan, Chan Eunice, Srivatsa Vikranth, Ghosh Dhruba, Yang Yaoqing, Yu Yaodong, Zhong Ruiqi, Gonzalez Joseph E., Steinhardt Jacob
conference: "Arxiv"
year: 2021
bibkey: pham2021effect
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.04094"}
tags: ['BERT', 'Model Architecture', 'Uncategorized']
---
Overparameterization is shown to result in poor test accuracy on rare
subgroups under a variety of settings where subgroup information is known. To
gain a more complete picture, we consider the case where subgroup information
is unknown. We investigate the effect of model size on worst-group
generalization under empirical risk minimization (ERM) across a wide range of
settings, varying: 1) architectures (ResNet, VGG, or BERT), 2) domains (vision
or natural language processing), 3) model size (width or depth), and 4)
initialization (with pre-trained or random weights). Our systematic evaluation
reveals that increasing model size does not hurt, and may help, worst-group
test performance under ERM across all setups. In particular, increasing
pre-trained model size consistently improves performance on Waterbirds and
MultiNLI. We advise practitioners to use larger pre-trained models when
subgroup labels are unknown.
