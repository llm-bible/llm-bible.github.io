---
layout: publication
title: 'Optimizing Encoder-only Transformers For Session-based Recommendation Systems'
authors: Anis Redjdal, Luis Pinto, Michel Desmarais
conference: "Arxiv"
year: 2024
bibkey: redjdal2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11150"}
tags: ['Masked Language Model', 'Pretraining Methods', 'Model Architecture', 'Transformer']
---
Session-based recommendation is the task of predicting the next item a user
will interact with, often without access to historical user data. In this work,
we introduce Sequential Masked Modeling, a novel approach for encoder-only
transformer architectures to tackle the challenges of single-session
recommendation. Our method combines data augmentation through window sliding
with a unique penultimate token masking strategy to capture sequential
dependencies more effectively. By enhancing how transformers handle session
data, Sequential Masked Modeling significantly improves next-item prediction
performance.
  We evaluate our approach on three widely-used datasets, Yoochoose 1/64,
Diginetica, and Tmall, comparing it to state-of-the-art single-session,
cross-session, and multi-relation approaches. The results demonstrate that our
Transformer-SMM models consistently outperform all models that rely on the same
amount of information, while even rivaling methods that have access to more
extensive user history. This study highlights the potential of encoder-only
transformers in session-based recommendation and opens the door for further
improvements.
