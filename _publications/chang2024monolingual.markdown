---
layout: publication
title: Goldfish Monolingual Language Models For 350 Languages
authors: Chang Tyler A., Arnett Catherine, Tu Zhuowen, Bergen Benjamin K.
conference: "Arxiv"
year: 2024
bibkey: chang2024monolingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10441"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
For many low45;resource languages the only available language models are large multilingual models trained on many languages simultaneously. However using FLORES perplexity as a metric we find that these models perform worse than bigrams for many languages (e.g. 2437; of languages in XGLM 4.5B; 4337; in BLOOM 7.1B). To facilitate research that focuses on low45;resource languages we pre45;train and release Goldfish a suite of monolingual autoregressive Transformer language models up to 125M parameters for 350 languages. The Goldfish reach lower FLORES perplexities than BLOOM XGLM and MaLA45;500 on 98 of 204 FLORES languages despite each Goldfish model being over 10x smaller. However the Goldfish significantly underperform larger multilingual models on reasoning benchmarks suggesting that for low45;resource languages multilinguality primarily improves general reasoning abilities rather than basic text generation. We release models trained on 5MB (350 languages) 10MB (288 languages) 100MB (166 languages) and 1GB (83 languages) of text data where available. The Goldfish models are available as baselines fine45;tuning sources or augmentations to existing models in low45;resource NLP research and they are further useful for crosslinguistic studies requiring maximally comparable models across languages.
