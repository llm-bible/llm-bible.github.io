---
layout: publication
title: 'Do Compressed Llms Forget Knowledge? An Experimental Study With Practical Implications'
authors: Hoang Duc N. M, Cho Minsik, Merth Thomas, Rastegari Mohammad, Wang Zhangyang
conference: "Arxiv"
year: 2023
bibkey: hoang2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00867"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Compressing Large Language Models (LLMs) often leads to reduced performance,
especially for knowledge-intensive tasks. In this work, we dive into how
compression damages LLMs' inherent knowledge and the possible remedies. We
start by proposing two conjectures on the nature of the damage: one is certain
knowledge being forgotten (or erased) after LLM compression, hence
necessitating the compressed model to (re)learn from data with additional
parameters; the other presumes that knowledge is internally displaced and hence
one requires merely "inference re-direction" with input-side augmentation such
as prompting, to recover the knowledge-related performance. Extensive
experiments are then designed to (in)validate the two conjectures. We observe
the promise of prompting in comparison to model tuning; we further unlock
prompting's potential by introducing a variant called Inference-time Dynamic
Prompting (IDP), that can effectively increase prompt diversity without
incurring any inference overhead. Our experiments consistently suggest that
compared to the classical re-training alternatives such as LoRA, prompting with
IDP leads to better or comparable post-compression performance recovery, while
saving the extra parameter size by 21x and reducing inference latency by 60%.
Our experiments hence strongly endorse the conjecture of "knowledge displaced"
over "knowledge forgotten", and shed light on a new efficient mechanism to
restore compressed LLM performance. We additionally visualize and analyze the
different attention and activation patterns between prompted and re-trained
models, demonstrating they achieve performance recovery in two different
regimes.
