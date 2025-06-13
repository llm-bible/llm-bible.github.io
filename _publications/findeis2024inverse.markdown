---
layout: publication
title: 'Inverse Constitutional AI: Compressing Preferences Into Principles'
authors: Arduin Findeis, Timo Kaufmann, Eyke Hüllermeier, Samuel Albanie, Robert Mullins
conference: "Arxiv"
year: 2024
bibkey: findeis2024inverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06560"}
  - {name: "Code", url: "https://github.com/rdnfn/icai"}
tags: ['Fine-Tuning', 'Tools', 'Ethics and Bias', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Feedback data is widely used for fine-tuning and evaluating state-of-the-art
AI models. Pairwise text preferences, where human or AI annotators select the
"better" of two options, are particularly common. Such preferences are used to
train (reward) models or to rank models with aggregate statistics. For many
applications it is desirable to understand annotator preferences in addition to
modelling them - not least because extensive prior work has shown various
unintended biases in preference datasets. Yet, preference datasets remain
challenging to interpret. Neither black-box reward models nor statistics can
answer why one text is preferred over another. Manual interpretation of the
numerous (long) response pairs is usually equally infeasible. In this paper, we
introduce the Inverse Constitutional AI (ICAI) problem, formulating the
interpretation of pairwise text preference data as a compression task. In
constitutional AI, a set of principles (a constitution) is used to provide
feedback and fine-tune AI models. ICAI inverts this process: given a feedback
dataset, we aim to extract a constitution that best enables a large language
model (LLM) to reconstruct the original annotations. We propose a corresponding
ICAI algorithm and validate its generated constitutions quantitatively based on
annotation reconstruction accuracy on several datasets: (a) synthetic feedback
data with known principles; (b) AlpacaEval cross-annotated human feedback data;
(c) crowdsourced Chatbot Arena data; and (d) PRISM data from diverse
demographic groups. As a short and interpretable representation of the original
dataset, generated constitutions have many potential use cases: help identify
undesirable annotator biases, understand model performance better, scale
feedback to unseen data, or adapt models to individual user or group
preferences. We release the source code at https://github.com/rdnfn/icai.
