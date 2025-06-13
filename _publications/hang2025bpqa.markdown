---
layout: publication
title: 'BPQA Dataset: Evaluating How Well Language Models Leverage Blood Pressures To Answer Biomedical Questions'
authors: Chi Hang, Ruiqi Deng, Lavender Yao Jiang, Zihao Yang, Anton Alyakin, Daniel Alber, Eric Karl Oermann
conference: "Arxiv"
year: 2025
bibkey: hang2025bpqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04155"}
tags: ['Transformer', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Pretraining Methods', 'BERT']
---
Clinical measurements such as blood pressures and respiration rates are
critical in diagnosing and monitoring patient outcomes. It is an important
component of biomedical data, which can be used to train transformer-based
language models (LMs) for improving healthcare delivery. It is, however,
unclear whether LMs can effectively interpret and use clinical measurements. We
investigate two questions: First, can LMs effectively leverage clinical
measurements to answer related medical questions? Second, how to enhance an
LM's performance on medical question-answering (QA) tasks that involve
measurements? We performed a case study on blood pressure readings (BPs), a
vital sign routinely monitored by medical professionals. We evaluated the
performance of four LMs: BERT, BioBERT, MedAlpaca, and GPT-3.5, on our newly
developed dataset, BPQA (Blood Pressure Question Answering). BPQA contains
\\(100\\) medical QA pairs that were verified by medical students and designed to
rely on BPs . We found that GPT-3.5 and MedAlpaca (larger and medium sized LMs)
benefit more from the inclusion of BPs than BERT and BioBERT (small sized LMs).
Further, augmenting measurements with labels improves the performance of
BioBERT and Medalpaca (domain specific LMs), suggesting that retrieval may be
useful for improving domain-specific LMs.
