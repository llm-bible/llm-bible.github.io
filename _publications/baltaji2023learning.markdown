---
layout: publication
title: 'Learning Transfers Over Several Programming Languages'
authors: Razan Baltaji, Saurabh Pujar, Louis Mandel, Martin Hirzel, Luca Buratti, Lav Varshney
conference: "Arxiv"
year: 2023
bibkey: baltaji2023learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.16937'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'In-Context Learning', 'Pretraining Methods']
---
Large language models (LLMs) have become remarkably good at improving
developer productivity for high-resource programming languages. These models
use two kinds of data: large amounts of unlabeled code samples for pre-training
and relatively smaller amounts of labeled code samples for fine-tuning or
in-context learning. Unfortunately, many programming languages are
low-resource, lacking labeled samples for most tasks and often even lacking
unlabeled samples. Therefore, users of low-resource languages (e.g., legacy or
new languages) miss out on the benefits of LLMs. Cross-lingual transfer uses
data from a source language to improve model performance on a target language.
It has been well-studied for natural languages, but has received little
attention for programming languages. This paper reports extensive experiments
on four tasks using a transformer-based LLM and 11 to 41 programming languages
to explore the following questions. First, how well does cross-lingual transfer
work for a given task across different language pairs. Second, given a task and
target language, how should one choose a source language. Third, which
characteristics of a language pair are predictive of transfer performance, and
how does that depend on the given task. Our empirical study with 1,808
experiments reveals practical and scientific insights, such as Kotlin and
JavaScript being the most transferable source languages and different tasks
relying on substantially different features. Overall, we find that learning
transfers well across several programming languages.
