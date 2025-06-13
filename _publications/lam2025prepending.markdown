---
layout: publication
title: 'Prepending Or Cross-attention For Speech-to-text? An Empirical Comparison'
authors: Tsz Kin Lam, Marco Gaido, Sara Papi, Luisa Bentivogli, Barry Haddow
conference: "Arxiv"
year: 2025
bibkey: lam2025prepending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02370"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'Attention Mechanism']
---
Following the remarkable success of Large Language Models (LLMs) in NLP
tasks, there is increasing interest in extending their capabilities to speech
-- the most common form of communication. The most widespread approach to
integrating speech into LLMs is dense feature prepending (DFP), which prepends
the projected speech representations to the textual representations, allowing
end-to-end training with a speech encoder. This raises questions about the need
for a sophisticated speech encoder for DFP and how its performance compares
with a standard encoder-decoder (i.e., cross-attention) architecture. We
compare DFP and cross-attention under a variety of configurations, such as CTC
compression, sequence-level knowledge distillation, on monolingual, bilingual,
and multilingual models. To perform a controlled architectural comparison, we
train all models from scratch rather than using large pretrained models and use
comparable data and parameter settings, testing speech-to-text recognition
(ASR) and translation (ST) on MuST-C v1.0 and CoVoST2 datasets. Despite the
wide adoption of DFP, our results do not indicate a clear advantage of DFP over
cross-attention.
