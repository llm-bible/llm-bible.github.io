---
layout: publication
title: Unraveling The Mechanics Of Learning45;based Demonstration Selection For In45;context Learning
authors: Liu Hui, Wang Wenya, Sun Hao, Tian Chris Xing, Kong Chenqi, Dong Xin, Li Haoliang
conference: "Arxiv"
year: 2024
bibkey: liu2024unraveling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11890"}
tags: ['Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated impressive in45;context learning (ICL) capabilities from few45;shot demonstration exemplars. While recent learning45;based demonstration selection methods have proven beneficial to ICL by choosing more useful exemplars their underlying mechanisms are opaque hindering efforts to address limitations such as high training costs and poor generalization across tasks. These methods generally assume the selection process captures similarities between the exemplar and the target instance however it remains unknown what kinds of similarities are captured and vital to performing ICL. To dive into this question we analyze the working mechanisms of the learning45;based demonstration selection methods and empirically identify two important factors related to similarity measurement 1) The ability to integrate different levels of task45;agnostic text similarities between the input of exemplars and test cases enhances generalization power across different tasks. 2) Incorporating task45;specific labels when measuring the similarities significantly improves the performance on each specific task. We validate these two findings through extensive quantitative and qualitative analyses across ten datasets and various LLMs. Based on our findings we introduce two effective yet simplified exemplar selection methods catering to task45;agnostic and task45;specific demands eliminating the costly LLM inference overhead.
