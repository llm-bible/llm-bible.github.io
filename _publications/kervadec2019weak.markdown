---
layout: publication
title: Weak Supervision Helps Emergence Of Word45;object Alignment And Improves Vision45;language Tasks
authors: Kervadec Corentin Liris, Antipov Grigory Liris, Baccouche Moez Liris, Wolf Christian Liris
conference: "Arxiv"
year: 2019
bibkey: kervadec2019weak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1912.03063"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The large adoption of the self45;attention (i.e. transformer model) and BERT45;like training principles has recently resulted in a number of high performing models on a large panoply of vision45;and45;language problems (such as Visual Question Answering (VQA) image retrieval etc.). In this paper we claim that these State45;Of45;The45;Art (SOTA) approaches perform reasonably well in structuring information inside a single modality but despite their impressive performances they tend to struggle to identify fine45;grained inter45;modality relationships. Indeed such relations are frequently assumed to be implicitly learned during training from application45;specific losses mostly cross45;entropy for classification. While most recent works provide inductive bias for inter45;modality relationships via cross attention modules in this work we demonstrate (1) that the latter assumption does not hold i.e. modality alignment does not necessarily emerge automatically and (2) that adding weak supervision for alignment between visual objects and words improves the quality of the learned models on tasks requiring reasoning. In particular we integrate an object45;word alignment loss into SOTA vision45;language reasoning models and evaluate it on two tasks VQA and Language45;driven Comparison of Images. We show that the proposed fine45;grained inter45;modality supervision significantly improves performance on both tasks. In particular this new learning signal allows obtaining SOTA45;level performances on GQA dataset (VQA task) with pre45;trained models without finetuning on the task and a new SOTA on NLVR2 dataset (Language45;driven Comparison of Images). Finally we also illustrate the impact of the contribution on the models reasoning by visualizing attention distributions.
