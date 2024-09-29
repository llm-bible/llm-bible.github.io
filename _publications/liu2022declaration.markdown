---
layout: publication
title: Declaration45;based Prompt Tuning For Visual Question Answering
authors: Liu Yuhang, Wei Wei, Peng Daowan, Zhu Feida
conference: "Arxiv"
year: 2022
bibkey: liu2022declaration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.02456"}
tags: ['Applications', 'BERT', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
In recent years the pre45;training45;then45;fine45;tuning paradigm has yielded immense success on a wide spectrum of cross45;modal tasks such as visual question answering (VQA) in which a visual45;language (VL) model is first optimized via self45;supervised task objectives e.g. masked language modeling (MLM) and image45;text matching (ITM) and then fine45;tuned to adapt to downstream task (e.g. VQA) via a brand45;new objective function e.g. answer prediction. The inconsistency of the objective forms not only severely limits the generalization of pre45;trained VL models to downstream tasks but also requires a large amount of labeled data for fine45;tuning. To alleviate the problem we propose an innovative VL fine45;tuning paradigm (named Declaration45;based Prompt Tuning abbreviated as DPT) which jointly optimizes the objectives of pre45;training and fine45;tuning of VQA model boosting the effective adaptation of pre45;trained VL models to the downstream task. Specifically DPT reformulates the objective form of VQA task via (1) textual adaptation which converts the given questions into declarative sentence45;form for prompt45;tuning and (2) task adaptation which optimizes the objective function of VQA problem in the manner of pre45;training phase. Experimental results on GQA dataset show that DPT outperforms the fine45;tuned counterpart by a large margin regarding accuracy in both fully45;supervised (2.6837;) and zero45;shot/few45;shot (over 3137;) settings. All the data and codes will be available to facilitate future research.
