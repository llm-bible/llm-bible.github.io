---
layout: publication
title: 'A Three-pronged Approach To Cross-lingual Adaptation With Multilingual Llms'
authors: Vaibhav Singh, Amrith Krishna, Karthika Nj, Ganesh Ramakrishnan
conference: "Arxiv"
year: 2024
bibkey: singh2024three
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.17377'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'In-Context Learning', 'Pretraining Methods']
---
Low-resource languages, by its very definition, tend to be under represented
in the pre-training corpora of Large Language Models. In this work, we
investigate three low-resource cross-lingual approaches that enable an LLM
adapt to tasks in previously unseen languages. Llama-2 is an LLM where Indic
languages, among many other language families, contribute to less than
\\(0.005%\\) of the total \\(2\\) trillion token pre-training corpora. In this work,
we experiment with the English-dominated Llama-2 for cross-lingual transfer to
three Indic languages, Bengali, Hindi, and Tamil as target languages. We study
three approaches for cross-lingual transfer, under ICL and fine-tuning. One, we
find that adding additional supervisory signals via a dominant language in the
LLM, leads to improvements, both under in-context learning and fine-tuning.
Two, adapting the target languages to word reordering may be beneficial under
ICL, but its impact diminishes with fine tuning. Finally, continued
pre-training in one low-resource language can improve model performance for
other related low-resource languages.
