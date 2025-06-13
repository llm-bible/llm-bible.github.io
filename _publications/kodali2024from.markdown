---
layout: publication
title: 'From Human Judgements To Predictive Models: Unravelling Acceptability In Code-mixed Sentences'
authors: Prashant Kodali, Anmol Goel, Likhith Asapu, Vamshi Krishna Bonagiri, Anirudh Govil, Monojit Choudhury, Ponnurangam Kumaraguru, Manish Shrivastava
conference: "Arxiv"
year: 2024
bibkey: kodali2024from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.05572'}
tags: ['GPT', 'Model Architecture', 'BERT', 'Training Techniques', 'Reinforcement Learning']
---
Current computational approaches for analysing or generating code-mixed
sentences do not explicitly model ``naturalness'' or ``acceptability'' of
code-mixed sentences, but rely on training corpora to reflect distribution of
acceptable code-mixed sentences. Modelling human judgement for the
acceptability of code-mixed text can help in distinguishing natural code-mixed
text and enable quality-controlled generation of code-mixed text. To this end,
we construct Cline - a dataset containing human acceptability judgements for
English-Hindi~(en-hi) code-mixed text. Cline is the largest of its kind with
16,642 sentences, consisting of samples sourced from two sources: synthetically
generated code-mixed text and samples collected from online social media. Our
analysis establishes that popular code-mixing metrics such as CMI, Number of
Switch Points, Burstines, which are used to filter/curate/compare code-mixed
corpora have low correlation with human acceptability judgements, underlining
the necessity of our dataset. Experiments using Cline demonstrate that simple
Multilayer Perceptron (MLP) models when trained solely using code-mixing
metrics as features are outperformed by fine-tuned pre-trained Multilingual
Large Language Models (MLLMs). Specifically, among Encoder models XLM-Roberta
and Bernice outperform IndicBERT across different configurations. Among
Encoder-Decoder models, mBART performs better than mT5, however Encoder-Decoder
models are not able to outperform Encoder-only models. Decoder-only models
perform the best when compared to all other MLLMS, with Llama 3.2 - 3B models
outperforming similarly sized Qwen, Phi models. Comparison with zero and
fewshot capabilitites of ChatGPT show that MLLMs fine-tuned on larger data
outperform ChatGPT, providing scope for improvement in code-mixed tasks.
Zero-shot transfer from En-Hi to En-Te acceptability judgments are better than
random baselines.
