---
layout: publication
title: Fairness45;guided Few45;shot Prompting For Large Language Models
authors: Ma Huan, Zhang Changqing, Bian Yatao, Liu Lemao, Zhang Zhirui, Zhao Peilin, Zhang Shu, Fu Huazhu, Hu Qinghua, Wu Bingzhe
conference: "Arxiv"
year: 2023
bibkey: ma2023fairness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.13217"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Large language models have demonstrated surprising ability to perform in45;context learning i.e. these models can be directly applied to solve numerous downstream tasks by conditioning on a prompt constructed by a few input45;output examples. However prior research has shown that in45;context learning can suffer from high instability due to variations in training examples example order and prompt formats. Therefore the construction of an appropriate prompt is essential for improving the performance of in45;context learning. In this paper we revisit this problem from the view of predictive bias. Specifically we introduce a metric to evaluate the predictive bias of a fixed prompt against labels or a given attributes. Then we empirically show that prompts with higher bias always lead to unsatisfactory predictive quality. Based on this observation we propose a novel search strategy based on the greedy search to identify the near45;optimal prompt for improving the performance of in45;context learning. We perform comprehensive experiments with state45;of45;the45;art mainstream models such as GPT45;3 on various downstream tasks. Our results indicate that our method can enhance the models in45;context learning performance in an effective and interpretable manner.
