---
layout: publication
title: 'An Investigation Of Language Model Interpretability Via Sentence Editing'
authors: Samuel Stevens, Yu Su
conference: "Arxiv"
year: 2020
bibkey: stevens2020investigation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.14039"}
  - {name: "Code", url: "https://github.com/samuelstevens/sentence-editing-interpretability"}
tags: ['Training Techniques', 'Model Architecture', 'Interpretability', 'BERT', 'Has Code', 'Interpretability and Explainability', 'Pre-Training', 'Attention Mechanism']
---
Pre-trained language models (PLMs) like BERT are being used for almost all
language-related tasks, but interpreting their behavior still remains a
significant challenge and many important questions remain largely unanswered.
In this work, we re-purpose a sentence editing dataset, where faithful
high-quality human rationales can be automatically extracted and compared with
extracted model rationales, as a new testbed for interpretability. This enables
us to conduct a systematic investigation on an array of questions regarding
PLMs' interpretability, including the role of pre-training procedure,
comparison of rationale extraction methods, and different layers in the PLM.
The investigation generates new insights, for example, contrary to the common
understanding, we find that attention weights correlate well with human
rationales and work better than gradient-based saliency in extracting model
rationales. Both the dataset and code are available at
https://github.com/samuelstevens/sentence-editing-interpretability to
facilitate future interpretability research.
