---
layout: publication
title: 'Multi-modal Experience Inspired AI Creation'
authors: Qian Cao, Xu Chen, Ruihua Song, Hao Jiang, Guang Yang, Zhao Cao
conference: "Arxiv"
year: 2022
bibkey: cao2022multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2209.02427'}
  - {name: "Code", url: 'https://github.com/Aman-4-Real/MMTG'}
tags: ['Attention Mechanism', 'Has Code', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning']
---
AI creation, such as poem or lyrics generation, has attracted increasing
attention from both industry and academic communities, with many promising
models proposed in the past few years. Existing methods usually estimate the
outputs based on single and independent visual or textual information. However,
in reality, humans usually make creations according to their experiences, which
may involve different modalities and be sequentially correlated. To model such
human capabilities, in this paper, we define and solve a novel AI creation
problem based on human experiences. More specifically, we study how to generate
texts based on sequential multi-modal information. Compared with the previous
works, this task is much more difficult because the designed model has to well
understand and adapt the semantics among different modalities and effectively
convert them into the output in a sequential manner. To alleviate these
difficulties, we firstly design a multi-channel sequence-to-sequence
architecture equipped with a multi-modal attention network. For more effective
optimization, we then propose a curriculum negative sampling strategy tailored
for the sequential inputs. To benchmark this problem and demonstrate the
effectiveness of our model, we manually labeled a new multi-modal experience
dataset. With this dataset, we conduct extensive experiments by comparing our
model with a series of representative baselines, where we can demonstrate
significant improvements in our model based on both automatic and
human-centered metrics. The code and data are available at:
\url\{https://github.com/Aman-4-Real/MMTG\}.
