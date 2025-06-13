---
layout: publication
title: 'Goldfish: Monolingual Language Models For 350 Languages'
authors: Tyler A. Chang, Catherine Arnett, Zhuowen Tu, Benjamin K. Bergen
conference: "Arxiv"
year: 2024
bibkey: chang2024monolingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10441"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Applications']
---
For many low-resource languages, the only available language models are large
multilingual models trained on many languages simultaneously. However, using
FLORES perplexity as a metric, we find that these models perform worse than
bigrams for many languages (e.g. 24% of languages in XGLM 4.5B; 43% in BLOOM
7.1B). To facilitate research that focuses on low-resource languages, we
pre-train and release Goldfish, a suite of monolingual autoregressive
Transformer language models up to 125M parameters for 350 languages. The
Goldfish reach lower FLORES perplexities than BLOOM, XGLM, and MaLA-500 on 98
of 204 FLORES languages, despite each Goldfish model being over 10x smaller.
However, the Goldfish significantly underperform larger multilingual models on
reasoning benchmarks, suggesting that for low-resource languages,
multilinguality primarily improves general reasoning abilities rather than
basic text generation. We release models trained on 5MB (350 languages), 10MB
(288 languages), 100MB (166 languages), and 1GB (83 languages) of text data
where available. The Goldfish models are available as baselines, fine-tuning
sources, or augmentations to existing models in low-resource NLP research, and
they are further useful for crosslinguistic studies requiring maximally
comparable models across languages.
