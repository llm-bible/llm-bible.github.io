---
layout: publication
title: 'Dont Add, Dont Miss: Effective Content Preserving Generation From Pre-selected Text Spans'
authors: Aviv Slobodkin, Avi Caciularu, Eran Hirsch, Ido Dagan
conference: "Arxiv"
year: 2023
bibkey: slobodkin2023dont
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09017"}
tags: ['Efficiency and Optimization', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Distillation']
---
The recently introduced Controlled Text Reduction (CTR) task isolates the
text generation step within typical summarization-style tasks. It does so by
challenging models to generate coherent text conforming to pre-selected content
within the input text (``highlights''). This framing enables increased
modularity in summarization-like tasks, allowing to couple a single CTR model
with various content-selection setups and modules. However, there are currently
no reliable CTR models, while the performance of the existing baseline for the
task is mediocre, falling short of practical utility. Here, we address this gap
by introducing a high-quality, open-source CTR model that tackles two prior key
limitations: inadequate enforcement of the content-preservation constraint, and
suboptimal silver training data. Addressing these, we amplify the
content-preservation constraint in both training, via RL, and inference, via a
controlled decoding strategy. Further, we substantially improve the silver
training data quality via GPT-4 distillation. Overall, pairing the distilled
dataset with the highlight-adherence strategies yields marked gains over the
current baseline, of up to 30 ROUGE-L points, providing a reliable CTR model
for downstream use.
