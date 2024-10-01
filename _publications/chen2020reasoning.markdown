---
layout: publication
title: 'Reasoning In Dialog: Improving Response Generation By Context Reading Comprehension'
authors: Chen Xiuying, Cui Zhi, Zhang Jiayi, Wei Chen, Cui Jianwei, Wang Bin, Zhao Dongyan, Yan Rui
conference: "AAAI"
year: 2020
bibkey: chen2020reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.07410"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
"In multi-turn dialog, utterances do not always take the full form of sentences \cite\{Carbonell1983DiscoursePA\}, which naturally makes understanding the dialog context more difficult. However, it is essential to fully grasp the dialog context to generate a reasonable response. Hence, in this paper, we propose to improve the response generation performance by examining the model's ability to answer a reading comprehension question, where the question is focused on the omitted information in the dialog. Enlightened by the multi-task learning scheme, we propose a joint framework that unifies these two tasks, sharing the same encoder to extract the common and task-invariant features with different decoders to learn task-specific features. To better fusing information from the question and the dialog history in the encoding part, we propose to augment the Transformer architecture with a memory updater, which is designed to selectively store and update the history dialog information so as to support downstream tasks. For the experiment, we employ human annotators to write and examine a large-scale dialog reading comprehension dataset. Extensive experiments are conducted on this dataset, and the results show that the proposed model brings substantial improvements over several strong baselines on both tasks. In this way, we demonstrate that reasoning can indeed help better response generation and vice versa. We release our large-scale dataset for further research."
