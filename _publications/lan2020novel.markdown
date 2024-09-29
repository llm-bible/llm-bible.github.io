---
layout: publication
title: PONE A Novel Automatic Evaluation Metric For Open45;domain Generative Dialogue Systems
authors: Lan Tian, Mao Xian-ling, Wei Wei, Gao Xiaoyan, Huang Heyan
conference: "Arxiv"
year: 2020
bibkey: lan2020novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.02399"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Open45;domain generative dialogue systems have attracted considerable attention over the past few years. Currently how to automatically evaluate them is still a big challenge problem. As far as we know there are three kinds of automatic methods to evaluate the open45;domain generative dialogue systems (1) Word45;overlap45;based metrics; (2) Embedding45;based metrics; (3) Learning45;based metrics. Due to the lack of systematic comparison it is not clear which kind of metrics are more effective. In this paper we will first measure systematically all kinds of automatic evaluation metrics over the same experimental setting to check which kind is best. Through extensive experiments the learning45;based metrics are demonstrated that they are the most effective evaluation metrics for open45;domain generative dialogue systems. Moreover we observe that nearly all learning45;based metrics depend on the negative sampling mechanism which obtains an extremely imbalanced and low45;quality dataset to train a score model. In order to address this issue we propose a novel and feasible learning45;based metric that can significantly improve the correlation with human judgments by using augmented POsitive samples and valuable NEgative samples called PONE. Extensive experiments demonstrate that our proposed evaluation method significantly outperforms the state45;of45;the45;art learning45;based evaluation methods with an average correlation improvement of 13.1837;. In addition we have publicly released the codes of our proposed method and state45;of45;the45;art baselines.
