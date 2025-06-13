---
layout: publication
title: 'Detecting Errors Through Ensembling Prompts (DEEP): An End-to-end LLM Framework For Detecting Factual Errors'
authors: Alex Chandler, Devesh Surve, Hui Su
conference: "Arxiv"
year: 2024
bibkey: chandler2024detecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13009'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Prompting', 'Applications', 'Survey Paper', 'Pretraining Methods']
---
Accurate text summarization is one of the most common and important tasks
performed by Large Language Models, where the costs of human review for an
entire document may be high, but the costs of errors in summarization may be
even greater. We propose Detecting Errors through Ensembling Prompts (DEEP) -
an end-to-end large language model framework for detecting factual errors in
text summarization. Our framework uses a diverse set of LLM prompts to identify
factual inconsistencies, treating their outputs as binary features, which are
then fed into ensembling models. We then calibrate the ensembled models to
produce empirically accurate probabilities that a text is factually consistent
or free of hallucination. We demonstrate that prior models for detecting
factual errors in summaries perform significantly worse without optimizing the
thresholds on subsets of the evaluated dataset. Our framework achieves
state-of-the-art (SOTA) balanced accuracy on the AggreFact-XSUM FTSOTA,
TofuEval Summary-Level, and HaluEval Summarization benchmarks in detecting
factual errors within transformer-generated text summaries. It does so without
any fine-tuning of the language model or reliance on thresholding techniques
not available in practical settings.
