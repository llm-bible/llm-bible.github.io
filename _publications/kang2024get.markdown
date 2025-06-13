---
layout: publication
title: 'Get More For Less: Principled Data Selection For Warming Up Fine-tuning In Llms'
authors: Feiyang Kang, Hoang Anh Just, Yifan Sun, Himanshu Jahagirdar, Yuanzhi Zhang, Rongxing Du, Anit Kumar Sahu, Ruoxi Jia
conference: "Arxiv"
year: 2024
bibkey: kang2024get
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.02774'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/DV4LLM-D761/'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Applications', 'Merging', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
This work focuses on leveraging and selecting from vast, unlabeled, open data
to pre-fine-tune a pre-trained language model. The goal is to minimize the need
for costly domain-specific data for subsequent fine-tuning while achieving
desired performance levels. While many data selection algorithms have been
designed for small-scale applications, rendering them unsuitable for our
context, some emerging methods do cater to language data scales. However, they
often prioritize data that aligns with the target distribution. While this
strategy may be effective when training a model from scratch, it can yield
limited results when the model has already been pre-trained on a different
distribution. Differing from prior work, our key idea is to select data that
nudges the pre-training distribution closer to the target distribution. We show
the optimality of this approach for fine-tuning tasks under certain conditions.
We demonstrate the efficacy of our methodology across a diverse array of tasks
(NLU, NLG, zero-shot) with models up to 2.7B, showing that it consistently
surpasses other selection methods. Moreover, our proposed method is
significantly faster than existing techniques, scaling to millions of samples
within a single GPU hour. Our code is open-sourced (Code repository:
https://anonymous.4open.science/r/DV4LLM-D761/ ). While fine-tuning offers
significant potential for enhancing performance across diverse tasks, its
associated costs often limit its widespread adoption; with this work, we hope
to lay the groundwork for cost-effective fine-tuning, making its benefits more
accessible.
