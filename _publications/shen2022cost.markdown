---
layout: publication
title: 'COST-EFF: Collaborative Optimization Of Spatial And Temporal Efficiency With Slenderized Multi-exit Language Models'
authors: Bowen Shen, Zheng Lin, Yuanxin Liu, Zhengxiao Liu, Lei Wang, Weiping Wang
conference: "Arxiv"
year: 2022
bibkey: shen2022cost
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.15523'}
tags: ['Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'BERT', 'Quantization', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformer-based pre-trained language models (PLMs) mostly suffer from
excessive overhead despite their advanced capacity. For resource-constrained
devices, there is an urgent need for a spatially and temporally efficient model
which retains the major capacity of PLMs. However, existing statically
compressed models are unaware of the diverse complexities between input
instances, potentially resulting in redundancy and inadequacy for simple and
complex inputs. Also, miniature models with early exiting encounter challenges
in the trade-off between making predictions and serving the deeper layers.
Motivated by such considerations, we propose a collaborative optimization for
PLMs that integrates static model compression and dynamic inference
acceleration. Specifically, the PLM is slenderized in width while the depth
remains intact, complementing layer-wise early exiting to speed up inference
dynamically. To address the trade-off of early exiting, we propose a joint
training approach that calibrates slenderization and preserves contributive
structures to each exit instead of only the final layer. Experiments are
conducted on GLUE benchmark and the results verify the Pareto optimality of our
approach at high compression and acceleration rate with 1/8 parameters and 1/19
FLOPs of BERT.
