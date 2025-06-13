---
layout: publication
title: 'Learn From Failure: Fine-tuning Llms With Trial-and-error Data For Intuitionistic Propositional Logic Proving'
authors: Chenyang An, Zhibo Chen, Qihao Ye, Emily First, Letian Peng, Jiayun Zhang, Zihan Wang, Sorin Lerner, Jingbo Shang
conference: "Arxiv"
year: 2024
bibkey: an2024learn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07382"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
Recent advances in Automated Theorem Proving have shown the effectiveness of
leveraging a (large) language model that generates tactics (i.e. proof steps)
to search through proof states. The current model, while trained solely on
successful proof paths, faces a discrepancy at the inference stage, as it must
sample and try various tactics at each proof state until finding success,
unlike its training which does not incorporate learning from failed attempts.
Intuitively, a tactic that leads to a failed search path would indicate that
similar tactics should receive less attention during the following trials. In
this paper, we demonstrate the benefit of training models that additionally
learn from failed search paths. Facing the lack of such trial-and-error data in
existing open-source theorem-proving datasets, we curate a dataset on
intuitionistic propositional logic theorems and formalize it in Lean, such that
we can reliably check the correctness of proofs. We compare our model trained
on relatively short trial-and-error information (TrialMaster) with models
trained only on the correct paths and discover that the former solves more
unseen theorems with lower trial searches.
