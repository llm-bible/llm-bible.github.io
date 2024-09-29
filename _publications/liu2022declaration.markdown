---
layout: publication
title: Declaration-based Prompt Tuning For Visual Question Answering
authors: Liu Yuhang, Wei Wei, Peng Daowan, Zhu Feida
conference: "Arxiv"
year: 2022
bibkey: liu2022declaration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.02456"}
tags: ['Applications', 'BERT', 'Few Shot', 'Fine Tuning', 'Language Modeling', 'Masked Language Model', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
In recent years the pre-training-then-fine-tuning paradigm has yielded immense success on a wide spectrum of cross-modal tasks such as visual question answering (VQA) in which a visual-language (VL) model is first optimized via self-supervised task objectives e.g. masked language modeling (MLM) and image-text matching (ITM) and then fine-tuned to adapt to downstream task (e.g. VQA) via a brand-new objective function e.g. answer prediction. The inconsistency of the objective forms not only severely limits the generalization of pre-trained VL models to downstream tasks but also requires a large amount of labeled data for fine-tuning. To alleviate the problem we propose an innovative VL fine-tuning paradigm (named Declaration-based Prompt Tuning abbreviated as DPT) which jointly optimizes the objectives of pre-training and fine-tuning of VQA model boosting the effective adaptation of pre-trained VL models to the downstream task. Specifically DPT reformulates the objective form of VQA task via (1) textual adaptation which converts the given questions into declarative sentence-form for prompt-tuning and (2) task adaptation which optimizes the objective function of VQA problem in the manner of pre-training phase. Experimental results on GQA dataset show that DPT outperforms the fine-tuned counterpart by a large margin regarding accuracy in both fully-supervised (2.6837;) and zero-shot/few-shot (over 3137;) settings. All the data and codes will be available to facilitate future research.
