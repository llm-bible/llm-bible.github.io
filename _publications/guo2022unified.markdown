---
layout: publication
title: Unixcoder Unified Cross45;modal Pre45;training For Code Representation
authors: Guo Daya, Lu Shuai, Duan Nan, Wang Yanlin, Zhou Ming, Yin Jian
conference: "Arxiv"
year: 2022
bibkey: guo2022unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.03850"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre45;trained models for programming languages have recently demonstrated great success on code intelligence. To support both code45;related understanding and generation tasks recent works attempt to pre45;train unified encoder45;decoder models. However such encoder45;decoder framework is sub45;optimal for auto45;regressive tasks especially code completion that requires a decoder45;only manner for efficient inference. In this paper we present UniXcoder a unified cross45;modal pre45;trained model for programming language. The model utilizes mask attention matrices with prefix adapters to control the behavior of the model and leverages cross45;modal contents like AST and code comment to enhance code representation. To encode AST that is represented as a tree in parallel we propose a one45;to45;one mapping method to transform AST in a sequence structure that retains all structural information from the tree. Furthermore we propose to utilize multi45;modal contents to learn representation of code fragment with contrastive learning and then align representations among programming languages using a cross45;modal generation task. We evaluate UniXcoder on five code45;related tasks over nine datasets. To further evaluate the performance of code fragment representation we also construct a dataset for a new task called zero45;shot code45;to45;code search. Results show that our model achieves state45;of45;the45;art performance on most tasks and analysis reveals that comment and AST can both enhance UniXcoder.
